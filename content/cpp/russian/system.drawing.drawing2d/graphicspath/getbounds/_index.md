---
title: GetBounds()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает объект RectangleF, представляющий прямоугольник, ограничивающий путь, представленный текущим объектом, когда он преобразуется с помощью указанной матрицы.
type: docs
weight: 339
url: /ru/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const метод

Возвращает объект [RectangleF](../../../system.drawing/rectanglef/), представляющий прямоугольник, ограничивающий путь, представленный текущим объектом, когда он преобразуется с помощью указанной матрицы.

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Матрица преобразования |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | [Pen](../../../system.drawing/pen/) для вычисления ограничивающего прямоугольника. |

## См. также

* Typedef [MatrixPtr](../../matrixptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Pen](../../../system.drawing/pen/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)