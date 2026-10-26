---
title: DrawRectangle()
second_title: Справочник API Aspose.Slides для C++
description: Рисует указанный прямоугольник, используя указанное перо, на поверхности, представленной текущим объектом.
type: docs
weight: 287
url: /ru/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) method

Рисует указанный прямоугольник, используя указанный перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании прямоугольника |
| x | int | Координата X верхнего левого угла рисуемого прямоугольника |
| y | int | Координата Y верхнего левого угла рисуемого прямоугольника |
| width | int | Ширина рисуемого прямоугольника |
| height | int | Высота рисуемого прямоугольника |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) method

Рисует указанный прямоугольник, используя указанный перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании прямоугольника |
| x | **float** | Координата X верхнего левого угла рисуемого прямоугольника |
| y | **float** | Координата Y верхнего левого угла рисуемого прямоугольника |
| width | **float** | Ширина рисуемого прямоугольника |
| height | **float** | Высота рисуемого прямоугольника |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) method

Рисует указанный прямоугольник, используя указанный перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании прямоугольника |
| rect | [Rectangle](../../rectangle/) | Объект [Rectangle](../../rectangle/), который задает расположение и размер рисуемого прямоугольника |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)