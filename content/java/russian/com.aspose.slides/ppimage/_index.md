---
title: PPImage
second_title: Справочник API Aspose.Slides для Java
description: Представляет изображение в презентации.
type: docs
url: /ru/com.aspose.slides/ppimage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
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
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Заменяет данные изображения. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Заменяет данные изображения. |
| [getContentType()](#getContentType--) | Возвращает MIME-тип изображения, закодированный в  BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Возвращает ширину изображения. |
| [getHeight()](#getHeight--) | Возвращает высоту изображения. |
| [getX()](#getX--) | Возвращает смещение по X изображения. |
| [getY()](#getY--) | Возвращает смещение по Y изображения. |
| [hashCode()](#hashCode--) | Возвращает код хеша изображения. |
| [dispose()](#dispose--) | Освобождает объект. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Возвращает копию данных изображения. Только для чтения  byte[] .

**Возвращаемое значение:**
byte[] - Массив байтов
### getImage() {#getImage--}
```
public final IImage getImage()
```


Возвращает копию изображения. Только для чтения [IImage](../../com.aspose.slides/iimage).

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Это значение указывает, что изображение было создано из SVG.

**Возвращаемое значение:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Это значение указывает, что изображение было создано из SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Заменяет данные изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImageData | byte[] | Данные нового изображения. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Заменяет данные изображения. Внимание: когда Image является метафайлом - он будет растрирован. Используйте ReplaceImage(byte[]) вместо этого

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Новый объект изображения. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Заменяет данные изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Новый объект IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Возвращает MIME-тип изображения, закодированный в  BinaryData (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Возвращает ширину изображения. Только для чтения  int .

**Возвращаемое значение:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Возвращает высоту изображения. Только для чтения  int .

**Возвращаемое значение:**
int
### getX() {#getX--}
```
public final int getX()
```


Возвращает смещение по X изображения. Только для чтения  int .

**Возвращаемое значение:**
int
### getY() {#getY--}
```
public final int getY()
```


Возвращает смещение по Y изображения. Только для чтения  int .

**Возвращаемое значение:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает код хеша изображения.

**Возвращаемое значение:**
int - Код хеша.
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает объект.