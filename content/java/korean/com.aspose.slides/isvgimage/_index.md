---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: SVG 이미지를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

SVG 이미지를 나타냅니다.
## Methods

| Method | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | SVG 콘텐츠를 반환합니다. |
| [getSvgData()](#getSvgData--) | SVG 데이터를 반환합니다. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | SVG 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 인터페이스를 반환합니다. |
| [getBaseUri()](#getBaseUri--) | 지정된 SVG의 기본 URI를 반환합니다. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG 이미지를 EMF 파일로 저장합니다. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


SVG 콘텐츠를 반환합니다. 읽기 전용 String.

**Returns:**  
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


SVG 데이터를 반환합니다. 읽기 전용 byte[].

**Returns:**  
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


SVG 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 인터페이스를 반환합니다. 읽기 전용 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**  
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


지정된 SVG의 기본 URI를 반환합니다. 상대 링크를 해결하는 데 사용됩니다. 읽기 전용 String.

**Returns:**  
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


SVG 이미지를 EMF 파일로 저장합니다.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Creates the new SVG image
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Saves the SVG image as a metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Creates the new SVG image
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Saves the SVG image as a metafile
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |