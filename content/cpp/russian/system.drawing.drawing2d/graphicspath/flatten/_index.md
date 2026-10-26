---
title: Flatten()
second_title: Справочник API Aspose.Slides для C++
description: Сглаживает каждую кривую в пути, преобразуя её в серию соединённых линий. Значение плоскости 0.25 используется.
type: docs
weight: 391
url: /ru/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() метод

Сглаживает каждую кривую в пути, преобразуя её в серию соединённых линий. Значение плоскости 0.25 используется.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) метод

Сглаживает каждую кривую в пути, преобразуя её в серию соединённых линий. Значение плоскости 0.25 используется.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Матрица преобразования, применяемая к пути перед сглаживанием |

## GraphicsPath::Flatten(const MatrixPtr\&, float) метод

Сглаживает каждую кривую в пути, преобразуя её в серию соединённых линий.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Матрица преобразования, применяемая к пути перед сглаживанием |
| flatness | **float** | Задаёт максимально допустимую ошибку между кривой и её упрощённым приближением |

## См. также

* typedef [MatrixPtr](../../matrixptr/)
* Класс [GraphicsPath](../)
* Пространство имён [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)