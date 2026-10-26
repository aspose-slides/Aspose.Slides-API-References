---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: コンポーネントにライセンスを適用するためのメソッドを提供します。
type: docs
url: /ja/com.aspose.slides/ilicense/
---```
public interface ILicense
```

コンポーネントにライセンスを適用するためのメソッドを提供します。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | コンポーネントにライセンスを適用します。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを適用します。 |
| [resetLicense()](#resetLicense--) | ライセンスをリセットします |
| [isLicensed()](#isLicensed--) | コンポーネントにライセンスが適用されているか確認します |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

コンポーネントにライセンスを適用します。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licenseName | java.lang.String | 完全または短いファイル名、または埋め込みリソースの名前を指定できます。空文字列を使用すると評価モードに切り替わります。

--------------------

次の場所でライセンスを検索します：

1. 明示的なパス。
2. コンポーネント アセンブリのフォルダー。
3. クライアントの呼び出し側アセンブリのフォルダー。
4. エントリ アセンブリのフォルダー。
5. クライアントの呼び出し側アセンブリに埋め込まれたリソース。 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

コンポーネントにライセンスを適用します。

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ライセンスを含むストリーム。

--------------------

このメソッドを使用して、ストリームからライセンスをロードします。 |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

ライセンスをリセットします

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

このメソッドを使用して、コンポーネントのライセンスをリセットします

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

コンポーネントにライセンスが適用されているか確認します

**戻り値:**
boolean - コンポーネントがライセンスされている場合は true、そうでない場合は false