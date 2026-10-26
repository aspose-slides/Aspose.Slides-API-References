---
title: PPImage
second_title: Aspose.Slides для Android через Java API
description: Представляет изображение в презентации.
type: docs
url: /ru/com.aspose.slides/ppimage/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Представляет изображение в презентации.

## Методы

| Method | Description |
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
| [getX()](#getX--) | Возвращает X-смещение изображения. |
| [getY()](#getY--) | Возвращает Y-смещение изображения. |
| [hashCode()](#hashCode--) | Возвращает хеш-код изображения. |
| [dispose()](#dispose--) | Освобождает объект. |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Возвращает копию данных изображения. Только для чтения  byte[] .

**Возвращает:**
byte[] - Массив байтов

### getImage() {#getImage--}
```
public final IImage getImage()
```

Возвращает копию изображения. Только для чтения [IImage](../../com.aspose.slides/iimage).

**Возвращает:**
[IImage](../../com.aspose.slides/iimage)

### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Это значение указывает, что данное изображение было создано из SVG.

**Возвращает:**
[ISvgImage](../../com.aspose.slides/isvgimage)

### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

Возвращает или задает объект ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Это значение указывает, что данное изображение было создано из SVG.

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

Заменяет данные изображения. Внимание: когда Image является метафайлом - он будет растеризован. Используйте ReplaceImage(byte[]) вместо этого

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Новое изображение. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

Заменяет данные изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Новый IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Возвращает MIME-тип изображения, закодированный в  BinaryData (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращает:**
java.lang.String

### getWidth() {#getWidth--}
```
public final int getWidth()
```

Возвращает ширину изображения. Только для чтения  int .

**Возвращает:**
int

### getHeight() {#getHeight--}
```
public final int getHeight()
```

Возвращает высоту изображения. Только для чтения  int .

**Возвращает:**
int

### getX() {#getX--}
```
public final int getX()
```

Возвращает X-смещение изображения. Только для чтения  int .

**Возвращает:**
int

### getY() {#getY--}
```
public final int getY()
```

Возвращает Y-смещение изображения. Только для чтения  int .

**Возвращает:**
int

### hashCode() {#hashCode--}
```
public int hashCode()
```

Возвращает хеш-код изображения.

**Возвращает:**
int - Хеш-код.

### dispose() {#dispose--}
```
public final void dispose()
```

Освобождает объект.