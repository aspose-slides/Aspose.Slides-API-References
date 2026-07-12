---
title: IExternalResourceResolver
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: HTML および SVG ドキュメントのインポート中に外部リソースを解決するために使用されるコールバックインターフェイスです。
type: docs
url: /ja/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

HTML および SVG ドキュメントのインポート中に外部リソースを解決するために使用されるコールバックインターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | ベース URI と相対 URI から絶対 URI を解決します。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI を実際のリソースを含むオブジェクトにマッピングします。 |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


ベース URI と相対 URI から絶対 URI を解決します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | java.lang.String | リンク対象オブジェクトのベース URI |
| relativeUri | java.lang.String | リンクされたオブジェクトへの相対 URI。 |

**戻り値:**
java.lang.String - 相対 URI を解決できない場合は null を返す、絶対 URI。
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


URI を実際のリソースを含むオブジェクトにマッピングします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | オブジェクトへの絶対 URI。 |

**戻り値:**
java.io.InputStream - リソースをストリームできない場合は null を返す InputStream オブジェクト。