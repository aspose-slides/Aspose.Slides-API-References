---
title: VbaProject
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレゼンテーション マクロを含む VBA プロジェクトを表します。
type: docs
url: /ja/com.aspose.slides/vbaproject/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

プレゼンテーションマクロを含む VBA プロジェクトを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [VbaProject()](#VbaProject--) | This constructor creates new VBA project from scratch. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | This constructor loads VBA project from binary representation of OLE container. |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | Returns the name of the VBA project. |
| [getModules()](#getModules--) | Returns the list of all modules that are contained in the VBA project. |
| [getReferences()](#getReferences--) | Returns the list of all references that are contained in the VBA project. |
| [toBinary()](#toBinary--) | Returns the binary representation of the VBA project as OLE container |
| [isPasswordProtected()](#isPasswordProtected--) | Indicates whether the VBAProject is protected by a password to view project properties. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


This constructor creates new VBA project from scratch. Project will be created in 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


This constructor loads VBA project from binary representation of OLE container.

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Returns the name of the VBA project. 読み取り専用 String.

**戻り値:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Returns the list of all modules that are contained in the VBA project. 読み取り専用 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**戻り値:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Returns the list of all references that are contained in the VBA project. 読み取り専用 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**戻り値:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Returns the binary representation of the VBA project as OLE container

**戻り値:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indicates whether the VBAProject is protected by a password to view project properties. 読み取り専用  boolean .

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


**戻り値:**
boolean