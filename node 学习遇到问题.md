#node ������

## node ��ʲô
	
## node �����﷨

## node ��������
	1.JetBrains WebStorm 2016.3.2(64)
	2.HBuilder

## node ��������

## node Ӧ��
	1.����
## node web Ӧ��
	1.express 
	   ����https://gold.xitu.io/entry/5884ee911b69e60058e283a0
	   https://github.com/liumingmusic/react-native_toiletApp
	   ����������web�ˣ�app ��û���������ӿڿ�����
	2.

## node ����վ �� �õ�������վ
	1.https://cnodejs.org/	
	2.https://github.com/alsotang/node-lessons
	3.http://nodejs.cn/
	4.http://www.cnblogs.com/Leo_wl/p/4361289.html
	5.https://segmentfault.com/a/1190000000348772
	6.https://cnodejs.org/getstart/

## ��������
	ʹ��Nodeclipse����Express��Ŀ
	WebStorm 2016.3.2 

## one project

	֮�����в�������������ʵ�ֵ�
	1��express����
	1.1 npm��������

		1.��װnode�����https://nodejs.org/en
		2.��װ�Ա��˾���npm install -g cnpm --registry = https://registry.npm.taobao.org
		3.����ȫ�ֵ�npm�ӹ���������Դ�� npmrc������á�mac�����ַΪ /Users/liumingming/.npmrc���޸�strict-ssl=true �� registry=https://registry.npm.taobao.org

	1.2 express�����

		1.��װexpress-generator��npm install -g express-generator���û����ٴ���express��Ŀ
		2.������Ŀģ�飺���뵽��ĿĿ¼ /User/liumm/A_study/app/toiletApp ���棬ִ������ express -e service������-eΪejsģ���д
		3.�ڷ������Ŀ��װ����������������Ŀ /User/liumm/A_study/app/toiletApp/service ִ������ cnpm install����װ�������
		4.������Ŀ��ʹ���ڵ�ǰĿ¼��ʹ�� npm start������Ŀ������start������package.json�Ѿ�����
		5.Ԥ���������Ѿ��������ص� localhost:3000�����ʵ�ַ���ɿ���������ҳ��
		6.�޸�Ԥ������Ŀ��app.js �ļ�Ϊ�����������·�����޸���Ŀ���� views/index.ejs�ļ�������������в鿴
		7.express�޸��ȼ��أ���װsupervisor��npm install supervisor -g���޸���Ŀ�Զ�����

	���ݻ���֮��������裺http://blog.sina.com.cn/s/blog_a29eae2b0102vuey.html

	1.���̵Ĵ����� Ŀ¼Ϊthree
		express three -s
		
	2.cd three ���ļ���

	3.express -e three �������

	**����������
	4.npm install npm ���
	�Ӷ��������mysql ������������

	**����������
	5.npm init Ȼ���ʼ���� 

	6.����������� Ȼ�����json ��������� yes ����д��

	7.npm start �������ˡ�
	�Ϳ�������������ˣ�������л�ӭ�����ˡ�

	8.http://localhost:3000/ ������welcome �ˡ�

	���������ú������ļ������á���
	��blog 
	1.https://smm113522.github.io/2017/01/25/nodejs+express%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E6%94%BE%E5%BC%83/
	2.https://smm113522.github.io/2017/01/26/nodejs+express%E4%BB%8E%E6%94%BE%E5%BC%83%E5%88%B0%E5%85%A5%E9%97%A8%E6%80%9D%E8%80%83/

## WebStorm �п�����Ŀ
------------------------------------------------------------------
	node ��html ��֧��
	cmd���뵽��ĿĿ¼����װejs��npm install --save ejs
	��node js express ֧htmlģ��
	����ejs
	var ejs = require('ejs');
	ָ��html����
	app.engine('.html', ejs.__express);
	��ͼ����
	app.set('view engine', 'html');

	htmlҳ�������ejs��ͬ
	 <body>
	  <%=title%>
	 </body>
--------------------------------------------------------------
	���404 ҳ��
	app.js �����
	// 404
	app.get('*', function(req, res){
		res.render('404.html', {
			title: 'No Found'
		})
	});
----------------------------------------------------------------
	1.��װģ��
	npm install <Module Name> -����

	���������-g��ʾȫ�ְ�װ������ֻ�ǰ�װ��ĳ��Ŀ¼�¡�

	����ʵ��������ʹ�� npm ���װ���õ� Node.js web���ģ�� express
	2.ж��ģ��
	���ǿ���ʹ������������ж�� Node.js ģ�顣
	npm uninstall <Module Name>

	����ʹ�ð�װָ�װbootstrap:

	npm install bootstrap

	��ʹ��ж��ָ��ɾ��ģ�飺

	npm uninstall bootstrap

	���Ե� /node_modules/ Ŀ¼�²鿴���Ƿ񻹴���
	3.ģ���б�
	ʹ��ģ���б�������Է���Ŀ�����ǰ��Ŀ�������İ���
	npm ls
	5.����ģ��
	���ǿ���ʹ�������������ģ�飺
	npm update ģ������
	npm up -g ģ������
	6.����ģ��
	npm search ģ������
	7.����NPM ����
	��Ϊnpm�ķ������ڹ��⣬������״̬���õ����������һ��ģ�����Ϊ�����ӳٶ�ʧ�ܣ����Ը����ɹ����ٶȸ���ľ����������������ʹ���Ա� NPM ����http://npm.taobao.org/��Ϊ����

	npm install -g cnpm --registry=https://registry.npm.taobao.org
---------------------------------------------------------------------------------------------
	// app.engine('.html', ejs.__express);
	// app.set('view engine', 'html');
	
	ת���������ĺ�׺���ķ���
----------------------------------------------------------------------------------------------------


	 

##node ��ѧ�ļ��� 
	1.Jade ��һ�������ܵ�ģ�����棬������ Html Ӱ�죬������ JavaScript ʵ�ֵģ����ҿ��Թ� Node ʹ�á�
	https://segmentfault.com/a/1190000000357534
	2. html2jade
	http://html2jade.vida.io/
	http://www.html2jade.org/

## node ������̨
	����Nodejs+express4+Mongodb+Angularjs����web��Ŀ


## node������
	1��superagent	(http://visionmedia.github.io/superagent/ ) �Ǹ� http ����Ŀ⣬���Է��� get �� post ����

	2��cheerio		(https://github.com/cheeriojs/cheerio ) ��ҿ�������һ�� Node.js ��� jquery����������ҳ���� css selector ȡ���ݣ�ʹ�÷�ʽ�� jquery һ��һ���ġ�	

	3, express 		������ http://expressjs.com/ ���� Node.js Ӧ����㷺�� web ��ܣ������� 4.x �汾�����ǳ������� Rails ����������ȫ�������ˡ� 

	4��eventproxy   �����⣺superagent cheerio eventproxy(https://github.com/JacksonTian/eventproxy )	


## node �Ƽ��鼮

	����ǳһ��Node.js��
	�鼮��ַ<https://github.com/pana/node-books>

	
#java web ����

## ����
	������ http://www.eclipse.org/downloads/
	javaee �汾 ����
	iede ��ʹ�� �������µ� ��װ���ɣ�Ȼ���ƽ⼴����
	IntelliJ IDEA 2016.3.4(64) �java web ��Ŀ��app
	
## �����
	
	java web 
	IDEA �������http://www.cnblogs.com/carsonzhu/p/5468223.html��	
	eclipse �汾 http://www.cnblogs.com/hehaiyang/p/4578488.html
	idea ��׿Ҳ�����Ի��Ǻ���Ϥ�ġ�
	java maven 
	����http://blog.csdn.net/qq_32588349/article/details/51461182
	 archetypeCatalog=internal 
	java maven ���� web ��Ŀ��Ŀ
	http://www.micmiu.com/software/common/intellij-idea-create-maven-web/
	
	maven spring mvc ����
	http://www.cnblogs.com/Leo_wl/p/4459274.html
	
	
	
## �����﷨
	java �����ĺ���˼��ʹ��빹˼
	http://www.cnblogs.com/carsonzhu/p/5472159.html
	
	
## ��������

## Ӧ��

## web ���
	1.spring mvc
	2.spring boot
	
#php web ����

## �����﷨

##  Ӧ��

## ���

## �õ�ѧϰ��վ
1.http://lib.csdn.net/base/17



##  react-native android ����

## �����
	1.jdk 
	2.sdk
	win � http://www.jianshu.com/p/2fdc4655ddf8
	ѧϰ��ַ http://reactnative.cn/docs/0.20/getting-started.html
	React Native ����� ��鿴�������ϣ�
	http://reactnative.cn/docs/0.41/getting-started.html
	https://github.com/reactnativecn
	// ����������ʽ
	1.��������React Native Server 
	react-native start 
	2.���¿�һ���ն�(cmd), �л�����ĿĿ¼��װAPP 
	cd android
	gradlew.bat installDebug

    ִ��gradlew.bat installDebugʱ�����ȿ���Genymotionģ����
	3.������
	react-native run-android
## ���� 
	https://github.com/bigsui/shopping-react-native
	
	
	
	
	
## mysql

## ǰ��

## �õ�blog
http://yrq110.me/


