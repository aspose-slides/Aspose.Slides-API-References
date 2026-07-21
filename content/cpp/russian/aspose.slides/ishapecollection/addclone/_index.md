---
title: AddClone()
second_title: Справочник API Aspose.Slides для C++
description: Создает копию указанной формы и добавляет её в конец коллекции форм.
type: docs
weight: 495
url: /ru/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) метод

Создает копию указанной формы и добавляет её в конец коллекции форм.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Форма для клонирования. |
| x | **float** | Координата x кадра клонированной формы, в пунктах. |
| y | **float** | Координата y кадра клонированной формы, в пунктах. |
| width | **float** | Ширина кадра клонированной формы, в пунктах. |
| height | **float** | Высота кадра клонированной формы, в пунктах. |

### Возвращаемое значение

Новое созданное [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) метод

Создает копию указанной формы и добавляет её в конец коллекции форм. Новая форма сохраняет ширину и высоту *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для клонирования. |
| x | **float** | Координата x кадра клонированной формы, в пунктах. |
| y | **float** | Координата y кадра клонированной формы, в пунктах. |

### Возвращаемое значение

Новое созданное [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) метод

Создает копию указанной формы и добавляет её в конец коллекции форм. Клонированная форма сохраняет позицию и размер оригинала.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) для клонирования. |

### Возвращаемое значение

Новое созданное [IShape](../../ishape/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IShape](../../ishape/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)