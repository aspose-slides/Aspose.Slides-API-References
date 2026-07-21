---
title: AddClone()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.
type: docs
weight: 547
url: /ru/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Создает копию указанной фигуры и добавляет её в конец коллекции фигур.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Фигура для клонирования. |
| x | **float** | Координата x кадра новой фигуры, в пунктах. |
| y | **float** | Координата y кадра новой фигуры, в пунктах. |
| width | **float** | Ширина кадра новой фигуры, в пунктах. |
| height | **float** | Высота кадра новой фигуры, в пунктах. |

### Возвращаемое значение

Созданный [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

Создает копию указанной фигуры и добавляет её в конец коллекции фигур. Новая фигура сохраняет ширину и высоту *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Фигура для клонирования. |
| x | **float** | Координата x кадра новой фигуры, в пунктах. |
| y | **float** | Координата y кадра новой фигуры, в пунктах. |

### Возвращаемое значение

Созданный [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Создает копию указанной фигуры и добавляет её в конец коллекции фигур. Клонированная фигура сохраняет оригинальную позицию и размер.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для клонирования. |

### Возвращаемое значение

Созданный [IShape](../../ishape/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)