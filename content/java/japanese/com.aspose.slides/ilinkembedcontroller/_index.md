---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /ja/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

保存中にオブジェクトをどのように処理すべきかを決定するために使用されるコールバックインターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | オブジェクトをどこに保存すべきかを決定します。 |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | 外部オブジェクトへの URL を返します。 |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | 外部オブジェクトを保存します。 |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


オブジェクトをどこに保存すべきかを決定します。このメソッドは各オブジェクト ID ごとに 1 回呼び出されます。データ、semanticName、contentType が同一で ID が異なるオブジェクトが存在しないとは保証されません。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | int | オブジェクト ID。保存操作全体で一意です。 |
| entityData | byte[] | オブジェクトのバイナリ データ。オブジェクトのバイナリ データがまだ生成されていない場合は null にできます。 |
| semanticName | java.lang.String | オブジェクトの意味を表す短いテキスト。コントローラは外部オブジェクト名の一部として使用できるが、名前が一意で許可された文字のみを含むことを保証するのはディスパッチャの役割です。 |
| contentType | java.lang.String | オブジェクトの MIME タイプ。 |
| recomendedExtension | java.lang.String | この MIME タイプに推奨されるファイル拡張子。 |

**戻り値:**
int - 決定
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


外部オブジェクトへの URL を返します。このメソッドは #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) が [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) を返した場合に常に呼び出され、[LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) を返したが埋め込みが不可能な場合にも呼び出される可能性があります。同じオブジェクト ID に対して複数回呼び出すことができます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | int | オブジェクト ID。保存操作全体で一意です。 |
| referrer | int | 参照オブジェクトの ID、または 0（ルート ドキュメントから参照されている場合）。相対リンク生成に使用できる場合があります。 |

**戻り値:**
java.lang.String - 外部オブジェクトの URL、またはこのオブジェクトを無視すべき場合は null
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


外部オブジェクトを保存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | int | オブジェクト ID。保存操作全体で一意です。 |
| entityData | byte[] | オブジェクトのバイナリ データ。このパラメーターは null にできません。 |