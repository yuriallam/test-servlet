# Test Servlet

## Usage

- git clone the project
- Copy `test-servlet.war` to `webapps` directory in Apache Tomcat
- In Apache Tomcat, navigate to the `bin` folder and run `startup.bat`
- Open `index.html` in your browser

## Create WAR File

In the root of the project:

- Compile the `BonjourServlet.java` file with: `javac -d WEB-INF/classes -cp WEB-INF/lib/servlet-api.jar BonjourServlet.java`
- Generate the WAR file with: `jar -cvf test-servlet.war WEB-INF BonjourServlet.java`
<img width="521" alt="Screen Shot 2023-02-07 at 12 03 08 AM" src="https://user-images.githubusercontent.com/85178008/217100751-d4aa6e6b-f676-4914-a9bf-78877b39382b.png">
