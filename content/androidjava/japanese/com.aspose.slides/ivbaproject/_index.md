---
title: IVbaProject
second_title: Aspose.Slides for Android via Java API Reference
description: Represents VBA project with presentation macros.
type: docs
url: /ja/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

プレゼンテーションマクロを含む VBA プロジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | VBA プロジェクトの名前を返します。 |
| [getModules()](#getModules--) | VBA プロジェクトに含まれるすべてのモジュールのリストを返します。 |
| [getReferences()](#getReferences--) | VBA プロジェクトに含まれるすべての参照のリストを返します。 |
| [toBinary()](#toBinary--) | VBA プロジェクトのバイナリ表現を OLE コンテナとして返します。 |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject がプロジェクトのプロパティを表示するためのパスワードで保護されているかどうかを示します。 |
### getName() {#getName--}
```
public abstract String getName()
```


VBA プロジェクトの名前を返します。読み取り専用 String。

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


VBA プロジェクトに含まれるすべてのモジュールのリストを返します。読み取り専用 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)。

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


VBA プロジェクトに含まれるすべての参照のリストを返します。読み取り専用 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)。

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


VBA プロジェクトのバイナリ表現を OLE コンテナとして返します。読み取り専用 byte[]。

**Returns:**
byte[] - VBA プロジェクトのバイナリ表現（OLE コンテナとして）
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


VBAProject がプロジェクトのプロパティを表示するためのパスワードで保護されているかどうかを示します。読み取り専用 boolean。

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


**Returns:**
boolean