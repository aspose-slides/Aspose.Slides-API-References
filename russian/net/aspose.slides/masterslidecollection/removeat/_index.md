---
title: RemoveAt
second_title: Справочник по API Aspose.Slides для .NET
description: Удаляет элемент по указанному индексу коллекции.
type: docs
weight: 100
url: /ru/net/aspose.slides/masterslidecollection/removeat/
---
## MasterSlideCollection.RemoveAt method

Удаляет элемент по указанному индексу коллекции.

```csharp
public void RemoveAt(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Отсчитываемый от нуля индекс удаляемого элемента. |

### Исключения

| исключение | условие |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Генерируется, если удаляемый образец используется в презентации (его свойство HasDependingSlides равно true). |

### Примечания

Чтобы избежать создания PptxEditException, проверьте свойство HasDependingSlides мастера перед.

### Смотрите также

* class [MasterSlideCollection](../../masterslidecollection)
* пространство имен [Aspose.Slides](../../masterslidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
