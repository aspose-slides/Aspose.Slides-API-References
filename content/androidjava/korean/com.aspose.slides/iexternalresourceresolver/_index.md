---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: HTML 및 SVG 문서 가져오기 중 외부 리소스를 해결하는 데 사용하는 콜백 인터페이스입니다.
type: docs
url: /ko/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

HTML, SVG 문서 가져오기 중 외부 리소스를 해결하는 데 사용하는 콜백 인터페이스입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 기본 및 상대 URI에서 절대 URI를 해석합니다. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI를 실제 리소스를 포함하는 객체에 매핑합니다. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

기본 URI와 상대 URI에서 절대 URI를 해석합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | java.lang.String | 링크 객체의 기본 URI |
| relativeUri | java.lang.String | 링크된 객체에 대한 상대 URI |

**반환값:**
java.lang.String - 절대 URI 또는 상대 URI를 해석할 수 없을 경우 null.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

URI를 실제 리소스를 포함하는 객체에 매핑합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 객체에 대한 절대 URI |

**반환값:**
java.io.InputStream - InputStream 객체 또는 리소스를 스트리밍할 수 없을 경우 null.