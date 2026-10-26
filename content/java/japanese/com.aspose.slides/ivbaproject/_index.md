---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
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
| [getModules()](#getModules--) | VBA プロジェクトに含まれるすべてのモジュールの一覧を返します。 |
| [getReferences()](#getReferences--) | VBA プロジェクトに含まれるすべての参照の一覧を返します。 |
| [toBinary()](#toBinary--) | VBA プロジェクトのバイナリ表現を OLE コンテナとして返します。 |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject がプロジェクト プロパティの表示にパスワードで保護されているかどうかを示します。 |
### getName() {#getName--}
```
public abstract String getName()
```


VBA プロジェクトの名前を返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


VBA プロジェクトに含まれるすべてのモジュールの一覧を返します。読み取り専用 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)。

**戻り値:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


VBA プロジェクトに含まれるすべての参照の一覧を返します。読み取り専用 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)。

**戻り値:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


VBA プロジェクトのバイナリ表現を OLE コンテナとして返します。読み取り専用 byte[]。

**戻り値:**
byte[] - VBA プロジェクトのバイナリ表現を OLE コンテナとして
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


VBAProject がプロジェクト プロパティの表示にパスワードで保護されているかどうかを示します。読み取り専用 boolean。

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