---
title: Bitmap()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый объект Bitmap из указанного существующего изображения.
type: docs
weight: 1
url: /ru/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor


Создает новый объект [Bitmap](../) из указанного существующего изображения.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Существующее изображение, из которого создаётся растровое изображение. |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor


Создает новый объект [Bitmap](../) из указанного потока.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий данные изображения. |
| useIcm | **bool** | ИГНОРИРУЕТСЯ |

## Bitmap::Bitmap(const String\&) constructor


Создает новый объект [Bitmap](../) из указанного файла.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла, содержащего данные изображения. |

## Bitmap::Bitmap(const String\&, bool) constructor


Создает новый объект [Bitmap](../) из указанного файла.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла, содержащего данные изображения. |
| useIcm | **bool** | ИГНОРИРУЕТСЯ |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor


Создает новый объект [Bitmap](../), представляющий растровое изображение с указанными шириной, высотой, форматом пикселей и данными пикселей.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения |
| height | int | Высота изображения |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Формат пикселей изображения |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor


Создает новый объект [Bitmap](../) из указанного существующего изображения, масштабированного до указанного размера.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Существующее изображение, из которого создаётся растровое изображение. |
| size | const [Size](../../size/)\& | Размер нового изображения |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor


Создает новый объект [Bitmap](../) из указанного существующего изображения с шириной и высотой, масштабированными до указанных значений.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Существующее изображение, из которого создаётся растровое изображение. |
| width | int | Ширина нового изображения |
| height | int | Высота нового изображения |

## См. также

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)