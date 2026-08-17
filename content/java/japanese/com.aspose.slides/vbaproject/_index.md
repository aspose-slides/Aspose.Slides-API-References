---
title: VbaProject
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションマクロを含む VBA プロジェクトを表します。
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
| [VbaProject()](#VbaProject--) | このコンストラクタは新しい VBA プロジェクトをゼロから作成します。 |
| [VbaProject(byte[] data)](#VbaProject-byte---) | このコンストラクタは OLE コンテナのバイナリ表現から VBA プロジェクトをロードします。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | VBA プロジェクトの名前を返します。 |
| [getModules()](#getModules--) | VBA プロジェクトに含まれるすべてのモジュールの一覧を返します。 |
| [getReferences()](#getReferences--) | VBA プロジェクトに含まれるすべての参照の一覧を返します。 |
| [toBinary()](#toBinary--) | VBA プロジェクトのバイナリ表現（OLE コンテナ）を返します |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject がプロジェクト プロパティの表示にパスワードで保護されているかどうかを示します。 |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


このコンストラクタは新しい VBA プロジェクトをゼロから作成します。プロジェクトは 1252 Windows Latin 1（ANSI）コードページで作成されます

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


このコンストラクタは OLE コンテナのバイナリ表現から VBA プロジェクトをロードします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


VBA プロジェクトの名前を返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


VBA プロジェクトに含まれるすべてのモジュールの一覧を返します。読み取り専用 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)。

**戻り値:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


VBA プロジェクトに含まれるすべての参照の一覧を返します。読み取り専用 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)。

**戻り値:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


VBA プロジェクトのバイナリ表現（OLE コンテナ）を返します

**戻り値:**
byte[] - VBA プロジェクトのバイナリ表現（OLE コンテナ）
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


VBAProject がプロジェクト プロパティの表示にパスワードで保護されているかどうかを示します。読み取り専用 boolean 。

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