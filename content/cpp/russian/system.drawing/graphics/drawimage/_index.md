---
title: DrawImage()
second_title: Справочник API Aspose.Slides для C++
description: НЕ РЕАЛИЗОВАНО.
type: docs
weight: 430
url: /ru/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ИГНОРИРОВАНО |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | ИГНОРИРОВАНО |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Массив, содержащий три точки, определяющие параллелограмм на поверхности рисования, куда будет отрисовано изображение |
| srcRect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Указывает информацию о цвете и гамме изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Представление массива, содержащего три точки, определяющие параллелограмм на поверхности рисования, куда будет отрисовано изображение |
| srcRect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Указывает информацию о цвете и гамме изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Стековый массив, содержащий три точки, определяющие параллелограмм на поверхности рисования, куда будет отрисовано изображение |
| srcRect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Указывает информацию о цвете и гамме изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) метод

Отрисовывает указанное изображение в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | int | Координата X левого верхнего угла отрисованного изображения |
| y | int | Координата Y левого верхнего угла отрисованного изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) метод

Отрисовывает указанное изображение в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | **float** | Координата X левого верхнего угла отрисованного изображения |
| y | **float** | Координата Y левого верхнего угла отрисованного изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) метод

Отрисовывает указанное изображение в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| pt | [Point](../../point/) | Местоположение левого верхнего угла отрисованного изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) метод

Отрисовывает указанное изображение в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| pt | [PointF](../../pointf/) | Местоположение левого верхнего угла отрисованного изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) метод

Отрисовывает указанное изображение в указанный прямоугольник.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | int | Координата X левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| y | int | Координата Y левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| width | int | Ширина прямоугольника, в который будет отрисовано изображение |
| height | int | Высота прямоугольника, в который будет отрисовано изображение |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) метод

Отрисовывает указанное изображение в указанный прямоугольник.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | **float** | Координата X левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| y | **float** | Координата Y левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| width | **float** | Ширина прямоугольника, в который будет отрисовано изображение |
| height | **float** | Высота прямоугольника, в который будет отрисовано изображение |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destRect | [RectangleF](../../rectanglef/) | Прямоугольник, в который будет отрисовано изображение |
| srcRect | [RectangleF](../../rectanglef/) | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destRect | [Rectangle](../../rectangle/) | Прямоугольник, в который будет отрисовано изображение |
| srcRect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | int | Координата X левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| y | int | Координата Y левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| srcRect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) метод

Отрисовывает указанное изображение в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, в который будет отрисовано изображение |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) метод

Отрисовывает указанное изображение в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник, в который будет отрисовано изображение |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) метод

Отрисовывает указанную область указанного изображения в указанный прямоугольник.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destRect | [Rectangle](../../rectangle/) | Прямоугольник, в который будет отрисовано изображение |
| srcX | int | Координата X левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcY | int | Координата Y левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcWidth | int | Ширина прямоугольника, определяющего часть изображения для отрисовки |
| srcHeight | int | Высота прямоугольника, определяющего часть изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, в которых указаны параметры **srcX**, **srcY**, **srcWidth** и **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Указывает информацию о цвете и гамме изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) метод

Отрисовывает указанную область указанного изображения в указанный прямоугольник.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destRect | [Rectangle](../../rectangle/) | Прямоугольник, в который будет отрисовано изображение |
| srcX | **float** | Координата X левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcY | **float** | Координата Y левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcWidth | **float** | Ширина прямоугольника, определяющего часть изображения для отрисовки |
| srcHeight | **float** | Высота прямоугольника, определяющего часть изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, в которых указаны параметры **srcX**, **srcY**, **srcWidth** и **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Указывает информацию о цвете и гамме изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) метод

Отрисовывает указанную область указанного изображения в указанный прямоугольник.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destRect | [Rectangle](../../rectangle/) | Прямоугольник, в который будет отрисовано изображение |
| srcX | int | Координата X левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcY | int | Координата Y левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcWidth | int | Ширина прямоугольника, определяющего часть изображения для отрисовки |
| srcHeight | int | Высота прямоугольника, определяющего часть изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, в которых указаны параметры **srcX**, **srcY**, **srcWidth** и **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) метод

Отрисовывает указанную область указанного изображения в указанный прямоугольник.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destRect | [Rectangle](../../rectangle/) | Прямоугольник, в который будет отрисовано изображение |
| srcX | **float** | Координата X левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcY | **float** | Координата Y левого верхнего угла прямоугольника, определяющего часть изображения для отрисовки |
| srcWidth | **float** | Ширина прямоугольника, определяющего часть изображения для отрисовки |
| srcHeight | **float** | Высота прямоугольника, определяющего часть изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, в которых указаны параметры **srcX**, **srcY**, **srcWidth** и **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Массив, содержащий три точки, определяющие параллелограмм на поверхности рисования, куда будет отрисовано изображение |
| srcRect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Указывает информацию о цвете и гамме изображения |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) метод

Отрисовывает указанную область указанного изображения в указанном месте.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | **float** | Координата X левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| y | **float** | Координата Y левого верхнего угла прямоугольника, в который будет отрисовано изображение |
| srcRect | [RectangleF](../../rectanglef/) | Прямоугольник, определяющий область указанного изображения для отрисовки |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения, используемые параметром **srcRect** |

## См. также

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Класс [Image](../../image/)
* Класс [Point](../../point/)
* Класс [Graphics](../)
* Класс [PointF](../../pointf/)
* Класс [RectangleF](../../rectanglef/)
* Класс [Rectangle](../../rectangle/)
* Класс [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Пространство имён [System::Drawing](../../)
* Library [Aspose.Slides](../../../)