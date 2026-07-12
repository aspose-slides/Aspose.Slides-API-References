---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: 保存中にオブジェクトがどのように処理されるべきかを決定するために使用されるコールバックインターフェイスです。
type: docs
url: /ja/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

保存中にオブジェクトがどのように処理されるべきかを決定するために使用されるコールバックインターフェイスです。

## メソッド

| Method | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | オブジェクトを保存する場所を決定します。 |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | 外部オブジェクトへのURLを返します。 |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | 外部オブジェクトを保存します。 |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

オブジェクトを保存する場所を決定します。このメソッドは各オブジェクトIDにつき1回呼び出されます。データ、semanticName、contentType が同じで ID が異なるオブジェクトが存在しないことは保証されません。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | int | オブジェクトID。このIDは保存操作全体で一意です。 |
| entityData | byte[] | オブジェクトのバイナリデータ。このパラメータはオブジェクトのバイナリデータがまだ生成されていない場合はnullにできます。 |
| semanticName | java.lang.String | オブジェクトの意味を説明する短いテキスト。コントローラは外部オブジェクト名の一部として使用することがありますが、名前が一意で許可された文字のみを含むことを保証するのはディスパッチャの責任です。 |
| contentType | java.lang.String | オブジェクトのMIMEタイプ。 |
| recomendedExtension | java.lang.String | このMIMEタイプに推奨されるファイル名拡張子。 |

**戻り値:**
int - 決定

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

外部オブジェクトへのURLを返します。このメソッドは \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) が [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) を返した場合に必ず呼び出され、[LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) を返したが埋め込みが不可能な場合に呼び出される可能性があります。同じオブジェクトIDに対して複数回呼び出すことができます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | int | オブジェクトID。このIDは保存操作全体で一意です。 |
| referrer | int | 参照元オブジェクトのID、またはオブジェクトがルートドキュメントに参照されている場合は0です。相対リンクを生成するために使用できる場合があります。 |

**戻り値:**
java.lang.String - 外部オブジェクトのURL、またはこのオブジェクトを無視すべき場合はnull

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

外部オブジェクトを保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | int | オブジェクトID。このIDは保存操作全体で一意です。 |
| entityData | byte[] | オブジェクトのバイナリデータ。このパラメータはnullにできません。 |