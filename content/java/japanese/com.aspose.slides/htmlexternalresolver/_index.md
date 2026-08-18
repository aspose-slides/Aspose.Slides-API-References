---
title: HtmlExternalResolver
second_title: Aspose.Slides の Java API リファレンス
description: 画像などの参照オブジェクトを取得するために HTML インポートルーチンで使用されるコールバックオブジェクトです。
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

HTML インポートルーチンで、画像などの参照オブジェクトを取得するために使用されるコールバックオブジェクトです。

--------------------

このリゾルバを使用すると、クライアントが提供した HTML ファイルがサーバーソフトウェアにローカルまたはネットワーク上のファイルを取得させる脆弱性が生じる可能性があります。注意して使用してください。HtmlExternalResolver を指定しないこと（埋め込みオブジェクトのみが読み取られます）を推奨するか、指定された URI が有効かどうかをチェックするサブクラスを作成してください。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |

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
| baseUri | java.lang.String | リンクオブジェクトのベース URI |
| relativeUri | java.lang.String | リンクされたオブジェクトへの相対 URI |

**戻り値:**
java.lang.String - 絶対 URI、または相対 URI を解決できない場合は null

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

URI を実際のリソースを含むオブジェクトにマップします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | オブジェクトの絶対 URI |

**戻り値:**
java.io.InputStream - InputStream オブジェクト、またはリソースをストリームできない場合は null