---
title: PPImage
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션에서 이미지를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ppimage/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

프레젠테이션의 이미지를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 이미지 데이터의 복사본을 반환합니다. |
| [getImage()](#getImage--) | 이미지의 복사본을 반환합니다. |
| [getSvgImage()](#getSvgImage--) | ISvgImage 객체를 반환하거나 설정합니다 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage 객체를 반환하거나 설정합니다 [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 이미지 데이터를 교체합니다. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 이미지 데이터를 교체합니다. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 이미지 데이터를 교체합니다. |
| [getContentType()](#getContentType--) | 이미지의 MIME 유형을 반환합니다. BinaryData(\#getBinaryData.getBinaryData)로 인코딩됩니다. |
| [getWidth()](#getWidth--) | 이미지의 너비를 반환합니다. |
| [getHeight()](#getHeight--) | 이미지의 높이를 반환합니다. |
| [getX()](#getX--) | 이미지의 X-오프셋을 반환합니다. |
| [getY()](#getY--) | 이미지의 Y-오프셋을 반환합니다. |
| [hashCode()](#hashCode--) | 이미지의 해시 코드를 반환합니다. |
| [dispose()](#dispose--) | 객체를 해제합니다. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

이미지 데이터의 복사본을 반환합니다. 읽기 전용  byte[] .

**반환값:**
byte[] - 바이트 배열
### getImage() {#getImage--}
```
public final IImage getImage()
```

이미지의 복사본을 반환합니다. 읽기 전용 [IImage](../../com.aspose.slides/iimage).

**반환값:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

ISvgImage 객체를 반환하거나 설정합니다 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

이 값은 이미지가 SVG에서 생성되었음을 나타냅니다.

**반환값:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

ISvgImage 객체를 반환하거나 설정합니다 [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

이 값은 이미지가 SVG에서 생성되었음을 나타냅니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

이미지 데이터를 교체합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newImageData | byte[] | 새 이미지의 데이터. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

이미지 데이터를 교체합니다. 주의: 이미지가 메타파일인 경우 래스터화됩니다. 대신 ReplaceImage(byte[])를 사용하십시오.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 새 이미지. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

이미지 데이터를 교체합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 새 IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

이미지의 MIME 유형을 반환합니다. BinaryData(\#getBinaryData.getBinaryData)로 인코딩됩니다. 읽기 전용 String.

**반환값:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

이미지의 너비를 반환합니다. 읽기 전용  int .

**반환값:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

이미지의 높이를 반환합니다. 읽기 전용  int .

**반환값:**
int
### getX() {#getX--}
```
public final int getX()
```

이미지의 X-오프셋을 반환합니다. 읽기 전용  int .

**반환값:**
int
### getY() {#getY--}
```
public final int getY()
```

이미지의 Y-오프셋을 반환합니다. 읽기 전용  int .

**반환값:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

이미지의 해시 코드를 반환합니다.

**반환값:**
int - 해시 코드.
### dispose() {#dispose--}
```
public final void dispose()
```

객체를 해제합니다.