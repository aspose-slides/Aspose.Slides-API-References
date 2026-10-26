---
title: VbaProject
second_title: Aspose.Slides for Java API 參考
description: 表示具有簡報巨集的 VBA 專案。
type: docs
url: /zh-hant/com.aspose.slides/vbaproject/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

表示具有簡報巨集的 VBA 專案。
## 建構子

| 建構式 | 說明 |
| --- | --- |
| [VbaProject()](#VbaProject--) | 此建構式從頭建立新的 VBA 專案。 |
| [VbaProject(byte[] data)](#VbaProject-byte---) | 此建構式從 OLE 容器的二進位表示載入 VBA 專案。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getName()](#getName--) | 傳回 VBA 專案的名稱。 |
| [getModules()](#getModules--) | 傳回 VBA 專案中所有模組的清單。 |
| [getReferences()](#getReferences--) | 傳回 VBA 專案中所有參考的清單。 |
| [toBinary()](#toBinary--) | 傳回 VBA 專案的二進位表示 (OLE 容器) |
| [isPasswordProtected()](#isPasswordProtected--) | 指示 VBAProject 是否受到密碼保護以檢視專案屬性。 |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


此建構式從頭建立新的 VBA 專案。專案將以 1252 Windows Latin 1 (ANSI) 代碼頁建立

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


此建構式從 OLE 容器的二進位表示載入 VBA 專案。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


傳回 VBA 專案的名稱。唯讀 String。

**傳回值：**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


傳回 VBA 專案中所有模組的清單。唯讀 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)。

**傳回值：**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


傳回 VBA 專案中所有參考的清單。唯讀 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)。

**傳回值：**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


傳回 VBA 專案的二進位表示 (OLE 容器)

**傳回值：**
byte[] - VBA 專案的二進位表示 (OLE 容器)
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


指示 VBAProject 是否受到密碼保護以檢視專案屬性。唯讀 boolean 。

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


**傳回值：**
boolean