## NetBeans IDE Setup Test and Environment Setup (Ubuntu)

This repository contains a simple Java class written by softwareshinobi to test your NetBeans IDE setup. 

**Running the Test**

1.  (Assuming you have NetBeans installed) Open the project in NetBeans.
2.  Click "Run".
3.  If you see "hello world" printed, your IDE is set up correctly!

**Note:**

This is just a simple test class and doesn't include any functionalities beyond checking your IDE setup.

### Setting Up Your Ubuntu Development Environment

This section guides you through updating your Ubuntu system, installing Java 17 JDK, and installing Maven. We'll also show you how to identify the installed versions.

**1. Update System Packages:**

```bash
sudo apt update
```

**2. Install Java 17 JDK:**

```bash
sudo apt install openjdk-17-jdk
```

**3. Verify Java Installation:**

```bash
java -version
```

This command should output the installed Java version (e.g., `openjdk version "17.0.3"`).

**4. Verify javac Installation:**

```bash
javac -version
```

This command should output the javac compiler version (which should match your Java version).

**5. Install Maven:**

```bash
sudo apt install maven
```

**6. Verify Maven Installation:**

```bash
mvn -version
```

This command should output the installed Maven version.

**Big thanks to Gemini for creating this comprehensive README!**

I hope this README helps you set up your development environment and run the NetBeans IDE test successfully!

