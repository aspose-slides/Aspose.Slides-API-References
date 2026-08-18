---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API リファレンス
description: Html および Svg 文書のインポート中に外部リソースを解決するために使用されるコールバックインターフェイス。
type: docs
url: /ja/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Html および Svg 文書のインポート中に外部リソースを解決するために使用されるコールバックインターフェイス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | ベースURIと相対URIから絶対URIを解決します。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI を実際のリソースを含むオブジェクトにマッピングします。 |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

ベースURIと相対URIから絶対URIを解決します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | java.lang.String | リンク対象オブジェクトのベースURI |
| relativeUri | java.lang.String | リンクされたオブジェクトへの相対URI |

**戻り値:**
java.lang.String - 絶対URI、または相対URIを解決できない場合は null

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

URI を実際のリソースを含むオブジェクトにマッピングします。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | オブジェクトへの絶対URI |

**戻り値:**
java.io.InputStream - InputStream オブジェクト、またはリソースをストリーミングできない場合は null