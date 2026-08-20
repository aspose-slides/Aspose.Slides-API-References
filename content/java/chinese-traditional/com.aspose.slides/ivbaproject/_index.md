---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: 表示具有簡報巨集的 VBA 專案。
type: docs
url: /zh-hant/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

表示具有簡報巨集的 VBA 專案。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 返回 VBA 專案的名稱。 |
| [getModules()](#getModules--) | 返回包含於 VBA 專案中的所有模組的清單。 |
| [getReferences()](#getReferences--) | 返回包含於 VBA 專案中的所有參考的清單。 |
| [toBinary()](#toBinary--) | 返回 VBA 專案作為 OLE 容器的二進位表示。 |
| [isPasswordProtected()](#isPasswordProtected--) | 指示 VBAProject 是否受密碼保護以檢視專案屬性。 |
### getName() {#getName--}
```
public abstract String getName()
```


返回 VBA 專案的名稱。唯讀 String。

**返回：**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


返回包含於 VBA 專案中的所有模組的清單。唯讀 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)。

**返回：**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


返回包含於 VBA 專案中的所有參考的清單。唯讀 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)。

**返回：**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


返回 VBA 專案作為 OLE 容器的二進位表示。唯讀 byte[]。

**返回：**
byte[] - VBA 專案作為 OLE 容器的二進位表示
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


指示 VBAProject 是否受密碼保護以檢視專案屬性。唯讀 boolean。

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


**返回：**
boolean