# BasicJavaTutorial

환경 : CentOS Linux release 7.8.2003 (Core)   
개발도구 : vscode   

---
### 목적    

학부시절 배운 자바. 기본 재학습.   
코드를 정리하는건 의미가 없어보이므로 실행환경, 빌드환경, 빌드방법, JVM 설정 등을 요약해서 올리자

학습자료 : https://opentutorials.org/module/516/4551

---

### 자바 설치 및 버전 설정

yum install java-1.8.0-openjdk
yum install java-11-openjdk-devel

alternatives --config java


[root@janus alternatives]# alternatives --config java

There are 2 programs which provide 'java'.

  Selection    Command   
\-----------------------------------------------
*  1           java-1.8.0-openjdk.x86_64 (/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.275.b01-0.el7_9.x86_64/jre/bin/java)
 + 2           java-11-openjdk.x86_64 (/usr/lib/jvm/java-11-openjdk-11.0.9.11-2.el7_9.x86_64/bin/java)

Enter to keep the current selection[+], or type selection number:    여기에 숫자 입력후 엔터

---

### 빌드 및 실행

javac ${file}.java    
java ${file} ( 생성된 클래스 파일에서 .class 제외입력 )
