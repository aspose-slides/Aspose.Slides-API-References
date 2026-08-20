---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /ko/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Html 및 Svg 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 인터페이스입니다.
## 메서드

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 기초 URI 및 상대 URI에서 절대 URI를 해결합니다. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI를 실제 리소스를 포함하는 객체에 매핑합니다. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


기초 URI 및 상대 URI에서 절대 URI를 해결합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | 연결 객체의 기본 URI |
| relativeUri | java.lang.String | 연결된 객체에 대한 상대 URI. |

**Returns:**
java.lang.String - 절대 URI 또는 상대 URI를 해결할 수 없는 경우 null.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


URI를 실제 리소스를 포함하는 객체에 매핑합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | 객체에 대한 절대 URI. |

**Returns:**
java.io.InputStream - 스트림할 수 없는 경우 null인 InputStream 객체.