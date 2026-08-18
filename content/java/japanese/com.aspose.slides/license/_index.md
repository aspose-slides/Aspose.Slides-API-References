---
title: License
second_title: Aspose.Slides for Java API リファレンス
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
| [getVersion()](#getVersion--) | Aspose.Slides for Java のバージョンを返します。 |
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
| stream | java.io.InputStream | ライセンスを含むストリーム。null を指定すると評価モードに切り替わります。 |

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
| namePath | java.lang.String | フルパスまたは短縮ファイル名、埋め込みリソース名を指定できます。空文字列を指定すると評価モードに切り替わります。 |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Aspose.Slides for Java のバージョンを返します。

**戻り値:**  
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

ライセンスをリセットします。コンポーネント内のライセンスをリセットするためにこのメソッドを使用します。

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