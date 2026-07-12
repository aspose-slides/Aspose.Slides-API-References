---
title: ExternalResourceResolver
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: HTML および SVG ドキュメントのインポート時に外部リソースを解決するために使用されるコールバッククラスです。
type: docs
url: /ja/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

HTML および SVG ドキュメントのインポート時に外部リソースを解決するために使用されるコールバッククラスです。

--------------------

このリゾルバを使用すると、クライアントが提供した HTML または SVG ファイルによりサーバーソフトウェアがローカルまたはネットワーク上のファイルを取得できる脆弱性が生じる可能性があります。使用する際は注意が必要です。ExternalResourceResolver を指定しないこと（埋め込みオブジェクトのみが読み取られます）や、指定された URI が有効かどうかをチェックするサブクラスを作成することが推奨されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | ベースと相対 URI から絶対 URI を解決します。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI を実際のリソースを含むオブジェクトにマッピングします。 |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

ベース URI と相対 URI から絶対 URI を解決します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | java.lang.String | リンクするオブジェクトのベース URI |
| relativeUri | java.lang.String | リンクされたオブジェクトへの相対 URI |

**戻り値:**
java.lang.String - 絶対 URI または、相対 URI を解決できない場合は null

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

URI を実際のリソースを含むオブジェクトにマッピングします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | オブジェクトへの絶対 URI |

**戻り値:**
java.io.InputStream - InputStream オブジェクト、またはリソースをストリームできない場合は null