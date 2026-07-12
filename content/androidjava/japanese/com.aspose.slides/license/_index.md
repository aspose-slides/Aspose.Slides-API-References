---
title: License
second_title: Aspose.Slides for Android via Java API リファレンス
description: コンポーネントにライセンスを付与するためのメソッドを提供します。
type: docs
url: /ja/com.aspose.slides/license/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)  
```
public final class License implements ILicense
```

コンポーネントのライセンス付与のためのメソッドを提供します。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License--) | このクラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。 |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。 |
| [getVersion()](#getVersion--) | Java を介して Aspose.Slides for Android のバージョンを返します。 |
| [resetLicense()](#resetLicense--) | ライセンスをリセットします。 |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

このクラスの新しいインスタンスを初期化します。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

コンポーネントにライセンスを付与します。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ライセンスを含むストリームです。null を使用すると評価モードに切り替えられます。 |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

コンポーネントにライセンスを付与します。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| namePath | java.lang.String | フルパスまたは短いファイル名、埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替えられます。 |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Java を介して Aspose.Slides for Android のバージョンを返します。

**戻り値:**  
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

ライセンスをリセットします。コンポーネントのライセンスをリセットするためにこのメソッドを使用します。

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

コンポーネントにライセンスが適用されているか確認します。

**戻り値:**  
boolean