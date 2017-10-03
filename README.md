Exception in thread "main" java.lang.IllegalStateException: Specified firefox binary location does not exist or is not a real file: C:\Program Files\Java\jdk1.8.0_101\bin
	at com.google.common.base.Preconditions.checkState(Preconditions.java:174)
	at org.openqa.selenium.firefox.internal.Executable.<init>(Executable.java:46)
	at org.openqa.selenium.firefox.FirefoxBinary.<init>(FirefoxBinary.java:138)
	at org.openqa.selenium.firefox.FirefoxOptions.setBinary(FirefoxOptions.java:239)
	at org.openqa.selenium.firefox.FirefoxOptions.setBinary(FirefoxOptions.java:249)
	at org.openqa.selenium.firefox.FirefoxOptions.<init>(FirefoxOptions.java:169)
	at org.openqa.selenium.firefox.FirefoxDriver.<init>(FirefoxDriver.java:99)
	at newproject.PG2.main(PG2.java:12)
Picked up JAVA_TOOL_OPTIONS: -agentlib:jvmhook
Picked up _JAVA_OPTIONS: -Xrunjvmhook -Xbootclasspath/a:"C:\Program Files (x86)\HP\Unified Functional Testing\bin\java_shared\classes";"C:\Program Files (x86)\HP\Unified Functional Testing\bin\java_shared\classes\jasmine.jar"




Please help me out in rectifying it.
