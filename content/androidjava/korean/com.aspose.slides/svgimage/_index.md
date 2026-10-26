---
title: SvgImage
second_title: Aspose.Slides for Android용 Java API 참조
description: SVG 이미지를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/svgimage/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

SVG 이미지를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | 새 SvgImage 객체를 생성합니다. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | 새 SvgImage 객체를 생성합니다. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | 새 SvgImage 객체를 생성합니다. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 새 SvgImage 객체를 생성합니다. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 새 SvgImage 객체를 생성합니다. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 새 SvgImage 객체를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSvgData()](#getSvgData--) | SVG 데이터를 반환합니다. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Svg 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 인터페이스를 반환합니다. |
| [getBaseUri()](#getBaseUri--) | 지정된 Svg의 기본 URI를 반환합니다. |
| [getSvgContent()](#getSvgContent--) | SVG 콘텐츠를 반환합니다. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG 이미지를 EMF 파일로 저장합니다. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

새 SvgImage 객체를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | byte[] | Svg 데이터. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

새 SvgImage 객체를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg 콘텐츠. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

새 SvgImage 객체를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg 스트림. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

새 SvgImage 객체를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | byte[] | Svg 데이터. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| baseUri | java.lang.String | 지정된 Svg의 기본 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

새 SvgImage 객체를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg 콘텐츠. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| baseUri | java.lang.String | 지정된 Svg의 기본 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

새 SvgImage 객체를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg 스트림. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| baseUri | java.lang.String | 지정된 Svg의 기본 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

SVG 데이터를 반환합니다. 읽기 전용 byte[].

**반환값:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Svg 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 인터페이스를 반환합니다. 읽기 전용 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**반환값:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

지정된 Svg의 기본 URI를 반환합니다. 상대 링크를 해결하는 데 사용됩니다. 읽기 전용 String.

**반환값:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

SVG 콘텐츠를 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

SVG 이미지를 EMF 파일로 저장합니다.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // 새 SVG 이미지를 생성합니다
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // SVG 이미지를 메타파일로 저장합니다
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // 새 SVG 이미지를 생성합니다
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // SVG 이미지를 메타파일로 저장합니다
>      svgImage.writeAsEmf(byteStream);
>      // 이미지 컬렉션에 메타파일을 추가합니다
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |