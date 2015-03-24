# bcel_aop
bcel的aop监控方法调用使用时间
运行方式：
1.修改MANIFEST.MF：增加Premain-Class: Timing
2.java -cp . -Djava.ext.dirs=lib -javaagent:Timing.jar="helloWorld" Sample
