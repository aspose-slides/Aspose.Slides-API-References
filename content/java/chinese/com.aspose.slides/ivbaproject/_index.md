---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: 表示带有演示宏的 VBA 项目。
type: docs
url: /zh/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

表示带有演示宏的 VBA 项目。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 返回 VBA 项目的名称。 |
| [getModules()](#getModules--) | 返回 VBA 项目中包含的所有模块的列表。 |
| [getReferences()](#getReferences--) | 返回 VBA 项目中包含的所有引用的列表。 |
| [toBinary()](#toBinary--) | 返回 VBA 项目作为 OLE 容器的二进制表示。 |
| [isPasswordProtected()](#isPasswordProtected--) | 指示 VBAProject 是否通过密码受保护以查看项目属性。 |
### getName() {#getName--}
```
public abstract String getName()
```


返回 VBA 项目的名称。只读 String.

**返回:**  
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


返回 VBA 项目中包含的所有模块的列表。只读 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**返回:**  
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


返回 VBA 项目中包含的所有引用的列表。只读 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**返回:**  
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


返回 VBA 项目作为 OLE 容器的二进制表示。只读 byte[].

**返回:**  
byte[] - VBA 项目作为 OLE 容器的二进制表示
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


指示 VBAProject 是否通过密码受保护以查看项目属性。只读 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回:**  
boolean