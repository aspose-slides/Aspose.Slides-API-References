---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image in a presentation.
type: docs
url: /ko/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

프레젠테이션에서 이미지를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 이미지 데이터의 복사본을 반환합니다. |
| [getImage()](#getImage--) | 이미지의 복사본을 반환합니다. |
| [getSvgImage()](#getSvgImage--) | ISvgImage 객체 [ISvgImage](../../com.aspose.slides/isvgimage)를 반환하거나 설정합니다. |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage 객체 [ISvgImage](../../com.aspose.slides/isvgimage)를 반환하거나 설정합니다. |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 이미지 데이터를 교체합니다. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 이미지를 교체합니다. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 이미지를 교체합니다. |
| [getContentType()](#getContentType--) | 이미지의 MIME 유형을 반환합니다. \#getBinaryData.getBinaryData에 인코딩됩니다. |
| [getWidth()](#getWidth--) | 이미지의 너비를 반환합니다. |
| [getHeight()](#getHeight--) | 이미지의 높이를 반환합니다. |
| [getX()](#getX--) | 이미지의 X 오프셋을 반환합니다. |
| [getY()](#getY--) | 이미지의 Y 오프셋을 반환합니다. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


이미지 데이터의 복사본을 반환합니다. 읽기 전용 byte[].

**반환:**  
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


이미지 복사본을 반환합니다. 읽기 전용 \#getImage.getImage.

**반환:**  
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


ISvgImage 객체 [ISvgImage](../../com.aspose.slides/isvgimage)를 반환하거나 설정합니다.

--------------------

이 값은 이 이미지가 SVG에서 생성되었음을 나타냅니다.

**반환:**  
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


ISvgImage 객체 [ISvgImage](../../com.aspose.slides/isvgimage)를 반환하거나 설정합니다.

--------------------

이 값은 이 이미지가 SVG에서 생성되었음을 나타냅니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


이미지 데이터를 교체합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newImageData | byte[] | 새 이미지의 데이터. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


이미지를 교체합니다. 참고: 이미지가 메타파일인 경우 래스터화됩니다. 대신 replaceImage(byte[])를 사용하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 새 이미지. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


이미지를 교체합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 새 IPPImage. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


이미지의 MIME 유형을 반환합니다. \#getBinaryData.getBinaryData에 인코딩됩니다. 읽기 전용 String.

**반환:**  
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


이미지의 너비를 반환합니다. 읽기 전용 int.

**반환:**  
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


이미지의 높이를 반환합니다. 읽기 전용 int.

**반환:**  
int
### getX() {#getX--}
```
public abstract int getX()
```


이미지의 X 오프셋을 반환합니다. 읽기 전용 int.

**반환:**  
int
### getY() {#getY--}
```
public abstract int getY()
```


이미지의 Y 오프셋을 반환합니다. 읽기 전용 int.

**반환:**  
int