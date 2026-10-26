---
title: HtmlExternalResolver
second_title: Aspose.Slides for Android の Java API リファレンス
description: HTML インポート処理で画像などの参照オブジェクトを取得するために使用されるコールバック オブジェクト。
type: docs
url: /ja/com.aspose.slides/htmlexternalresolver/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

HTML インポート処理で画像などの参照オブジェクトを取得するために使用されるコールバック オブジェクト。

--------------------

このリゾルバーを使用すると、クライアントが提供した HTML ファイルがサーバー ソフトウェアにローカルまたはネットワーク ファイルを取得させる脆弱性が発生する可能性があります。注意して使用してください。HtmlExternalResolver を指定しないこと（埋め込みオブジェクトのみが読み取られる）を推奨するか、指定された URI が有効かどうかをチェックするサブクラスを作成してください。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | ベース URI と相対 URI から絶対 URI を解決します。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI を実際のリソースを含むオブジェクトにマッピングします。 |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


ベース URI と相対 URI から絶対 URI を解決します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseUri | java.lang.String | リンク オブジェクトのベース URI |
| relativeUri | java.lang.String | リンク先オブジェクトへの相対 URI。 |

**戻り値:**
java.lang.String - 絶対 URI または相対 URI を解決できない場合は null。
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


URI を実際のリソースを含むオブジェクトにマッピングします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | オブジェクトへの絶対 URI。 |

**戻り値:**
java.io.InputStream - InputStream オブジェクトまたはリソースをストリームできない場合は null。