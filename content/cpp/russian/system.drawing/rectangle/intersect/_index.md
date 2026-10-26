---
title: Intersect()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет прямоугольник, представленный текущим объектом, на прямоугольник, полученный в результате его пересечения с прямоугольником, представляемым указанным объектом.
type: docs
weight: 274
url: /ru/system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) метод

Заменяет прямоугольник, представленный текущим объектом, на прямоугольник, полученный в результате его пересечения с прямоугольником, представляемым указанным объектом.

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Объект [Rectangle](../), представляющий прямоугольник, с которым необходимо пересечь прямоугольник, представленный текущим объектом |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) метод

Возвращает прямоугольник, являющийся результатом пересечения указанных прямоугольников.

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const [Rectangle](../)\& | Первый прямоугольник для пересечения |
| b | const [Rectangle](../)\& | Второй прямоугольник для пересечения |

### Возвращаемое значение

Результат пересечения **a** с **b**

## См. также

* Класс [Rectangle](../)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)