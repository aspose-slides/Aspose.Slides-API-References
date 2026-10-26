---
title: InsertClone()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.
type: docs
weight: 508
url: /ru/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) метод

Создает копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой-based индекс, в который будет вставлена клонированная фигура. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Объект [IShape](../../ishape/) для клонирования. |
| x | **float** | Координата x рамки клонированной фигуры в пунктах. |
| y | **float** | Координата y рамки клонированной фигуры в пунктах. |
| width | **float** | Ширина рамки клонированной фигуры в пунктах. |
| height | **float** | Высота рамки клонированной фигуры в пунктах. |

### Возвращаемое значение

Созданный объект [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) метод

Создает копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. Новая фигура сохраняет ширину и высоту *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой-based индекс, в который будет вставлена клонированная фигура. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Объект [IShape](../../ishape/) для клонирования. |
| x | **float** | Координата x рамки клонированной фигуры в пунктах. |
| y | **float** | Координата y рамки клонированной фигуры в пунктах. |

### Возвращаемое значение

Созданный объект [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) метод

Создает копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. Клонированная фигура сохраняет позицию и размер оригинала.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой-based индекс, в который будет вставлена клонированная фигура. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Объект [IShape](../../ishape/) для клонирования. |

### Возвращаемое значение

Созданный объект [IShape](../../ishape/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)