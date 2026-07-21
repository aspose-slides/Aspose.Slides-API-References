---
title: Pen()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый объект Pen, представляющий указанный цвет.
type: docs
weight: 1
url: /ru/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) конструктор

Создает новый объект [Pen](../), представляющий указанный цвет.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Цвет пера, представленного объектом, который создаётся |

## Pen::Pen(const Color\&, float) конструктор

Создает новый объект [Pen](../), представляющий указанный цвет и ширину.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Цвет пера, представленного объектом, который создаётся |
| width | **float** | Ширина пера, представленного объектом, который создаётся |

## Pen::Pen(const SharedPtr\<Brush\>\&) конструктор

Создает новый объект [Pen](../) и инициализирует его указанным объектом [Brush](../../brush/).

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Объект [Brush](../../brush/), определяющий свойства заливки пера, представленного объектом, который создаётся |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) конструктор

Создает новый объект [Pen](../) и инициализирует его указанным объектом [Brush](../../brush/).

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Объект [Brush](../../brush/), определяющий свойства заливки пера, представленного объектом, который создаётся |
| width | **float** | Ширина пера, представленного объектом, который создаётся |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Color](../../color/)
* Класс [Pen](../)
* Класс [Brush](../../brush/)
* Пространство имен [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)