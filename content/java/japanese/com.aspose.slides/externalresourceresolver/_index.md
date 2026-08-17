---
title: ExternalResourceResolver
second_title: Aspose.Slides for Java API リファレンス
description: Html および Svg ドキュメントのインポート時に外部リソースを解決するために使用されるコールバッククラス。
type: docs
url: /ja/com.aspose.slides/externalresourceresolver/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Html および Svg ドキュメントのインポート中に外部リソースを解決するために使用されるコールバッククラス。

--------------------

このリゾルバを使用すると、クライアントが提供した HTML または SVG ファイルがサーバーソフトウェアにローカルまたはネットワーク上のファイルを取得させる脆弱性が生じる可能性があります。注意して使用してください。ExternalResourceResolver を指定しないこと（埋め込みオブジェクトのみが読み取られます）または、指定された uri が有効かどうかをチェックするサブクラスを作成することが推奨されます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | ベース URI と相対 URI から絶対 URI を解決します。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI を実際のリソースを含むオブジェクトにマッピングします。 |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

ベースと相対 URI から絶対 URI を解決します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | java.lang.String | リンクオブジェクトのベース URI |
| relativeUri | java.lang.String | リンクされたオブジェクトへの相対 URI。 |

**戻り値:**
java.lang.String - 絶対 URI または相対 URI を解決できない場合は null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

URI を実際のリソースを含むオブジェクトにマッピングします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | オブジェクトへの絶対 URI。 |

**戻り値:**
java.io.InputStream - InputStream オブジェクト、またはリソource をストリーミングできない場合は null。