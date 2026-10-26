---  
title: IPPImage  
second_title: Aspose.Slides for Android via Java API Reference  
description: Представляет изображение в презентации.  
type: docs  
url: /ru/com.aspose.slides/ippimage/  
---```
public interface IPPImage
```

Представляет изображение в презентации.  
## Методы

| Метод | Описание |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных изображения. |
| [getImage()](#getImage--) | Возвращает копию изображения. |
| [getSvgImage()](#getSvgImage--) | Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Заменяет данные изображения. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Заменяет изображение. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Заменяет изображение. |
| [getContentType()](#getContentType--) | Возвращает MIME-тип изображения, закодированный в \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Возвращает ширину изображения. |
| [getHeight()](#getHeight--) | Возвращает высоту изображения. |
| [getX()](#getX--) | Возвращает смещение X изображения. |
| [getY()](#getY--) | Возвращает смещение Y изображения. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Возвращает копию данных изображения. Только для чтения byte[].

**Возвращаемое значение:**  
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Возвращает копию изображения. Только для чтения \#getImage.getImage.

**Возвращаемое значение:**  
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Это значение указывает, что это изображение было создано из SVG.

**Возвращаемое значение:**  
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Это значение указывает, что это изображение было создано из SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Заменяет данные изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImageData | byte[] | Данные нового изображения. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Заменяет изображение. Внимание: когда Image является метафайлом, он будет растеризован. Вместо этого используйте replaceImage(byte[]) .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Новое изображение. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Заменяет изображение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Новый IPPImage. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Возвращает MIME-тип изображения, закодированный в \#getBinaryData.getBinaryData. Только для чтения String.

**Возвращаемое значение:**  
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Возвращает ширину изображения. Только для чтения int.

**Возвращаемое значение:**  
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Возвращает высоту изображения. Только для чтения int.

**Возвращаемое значение:**  
int
### getX() {#getX--}
```
public abstract int getX()
```

Возвращает смещение X изображения. Только для чтения int.

**Возвращаемое значение:**  
int
### getY() {#getY--}
```
public abstract int getY()
```

Возвращает смещение Y изображения. Только для чтения int.

**Возвращаемое значение:**  
int