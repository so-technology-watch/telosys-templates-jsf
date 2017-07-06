


# JSF - Telosys 3 Template

This template is used by [Telosys](http://www.telosys.org/) to generate a JSF (JavaServer Faces) which is a Java specification for web applications. You can find this template [here](https://github.com/so-technology-watch/telosys-templates-jsf).

## Prerequisites

* Java version 7/8
* Maven Project


## Installation

Refer to [Telosys Online Documentation](https://sites.google.com/site/telosystools/getting-started) to download and use the template.


## Template Configuration

#### For starting users

After generating all the necessary files to JSF [(Part 6 - Generate the code of Telosys documentation)](https://sites.google.com/site/telosystools/getting-started/generate-the-code).

Rename the original `pom.xml` to `pom_back.xml` and then change the `pom_jsf.xml` to `pom.xml`. 

And then run in terminal :
```bash
~ mvn clean install
```

Or for eclipse users execut :

* Maven clean
* Maven install

This will install all the dependencies used by the templates.

#### For advanced users

You can manually add the dependancies used by the project into your original `pom.xml` file.

Refer to the [depencies part](#dependencies-used) of the documentation

## Start the server

After genereating and setting up your projet, you can run it through a Tomcat or Apach server.  
This server must contain the argument : `-Denv.type.impl.jsf="default"`

The value of this argument can be : 
* jsf : `default`
* jsf-primefaces : `primefaces`
* jsf-richfaces : `richfaces`

Example for Primefaces implementation :  
`-Denv.type.impl.jsf="primefaces"`


## Dependencies used
 
 <table>
  <tbody>
    <tr>
      <th align="center">Dependencies</th>
      <th align="center">Version</th>
    </tr>
    <tr>
      <td>
      <a href="http://mvnrepository.com/artifact/com.sun.faces/jsf-api/2.2.2">jsf-api</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-2.2.2-brightgreen.svg" />
      </td>
    </tr>
        <tr>
      <td>
      <a href="http://mvnrepository.com/artifact/com.sun.faces/jsf-impl/2.2.2">jsf-impl</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-2.2.2-brightgreen.svg" />
      </td>
    </tr>
        <tr>
      <td>
      <a href="http://mvnrepository.com/artifact/javax.servlet/javax.servlet-api/3.0.1">javax.servlet-api</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-3.0.1-brightgreen.svg" />
      </td>
    </tr>
        <tr>
      <td>
      <a href="http://mvnrepository.com/artifact/org.primefaces/primefaces/6.0">primefaces</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-6.0-brightgreen.svg" />
      </td>
    </tr>
    <tr>
      <td>
      	<a href="http://mvnrepository.com/artifact/org.richfaces.ui/richfaces-components-ui/4.1.0.Final">richfaces-components-ui</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-4.1.0.Final-brightgreen.svg" />
      </td>
    </tr>
    <tr>
      <td>
      	<a href="http://mvnrepository.com/artifact/org.richfaces.core/richfaces-core-impl/4.1.0.Final">richfaces-core-impl</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-4.1.0.Final-brightgreen.svg" />
      </td>
    </tr>
    <tr>
      <td>
      	<a href="http://mvnrepository.com/artifact/org.webjars/bootstrap/3.3.7-1">bootstrap</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-3.3.7_1-brightgreen.svg" />
      </td>
    </tr>
  </tbody>
</table>
<br/>

