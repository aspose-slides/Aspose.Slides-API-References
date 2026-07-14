---
title: ExternalResourceResolver
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Html 및 Svg 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 클래스입니다.
type: docs
url: /ko/com.aspose.slides/externalresourceresolver/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Html 및 Svg 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 클래스입니다.

--------------------

이 리졸버를 사용하면 클라이언트가 제공한 HTML 또는 SVG 파일이 서버 소프트웨어가 로컬 또는 네트워크 파일을 가져오게 할 수 있어 취약점이 발생할 수 있습니다. 사용에 주의하십시오. ExternalResourceResolver를 전혀 지정하지 않는 것이 권장됩니다(내장 객체만 읽힙니다) 또는 지정된 uri가 유효한지 확인하는 서브클래스를 생성하십시오.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 베이스 및 상대 URI에서 절대 URI를 해결합니다. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | URI를 실제 리소스를 포함하는 객체에 매핑합니다. |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

베이스 및 상대 URI에서 절대 URI를 해결합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | java.lang.String | 링크 객체의 기본 URI |
| relativeUri | java.lang.String | 링크된 객체에 대한 상대 URI. |

**반환값:**
java.lang.String - 절대 URI 또는 상대 URI를 해결할 수 없는 경우 null.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

URI를 실제 리소스를 포함하는 객체에 매핑합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 객체에 대한 절대 URI. |

**반환값:**
java.io.InputStream - InputStream 객체 또는 리소스를 스트리밍할 수 없는 경우 null.