---
title: RemoveAt
second_title: Aspose.Sildes для .NET API Справочник
description: Удаляет элемент по указанному индексу из коллекции.
type: docs
weight: 60
url: /ru/aspose.slides/imasterlayoutslidecollection/removeat/
---

## IMasterLayoutSlideCollection.RemoveAt метод

Удаляет элемент по указанному индексу из коллекции.

```csharp
public void RemoveAt(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Нулевой основанный индекс элемента для удаления. |

### Исключения

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Выбрасывается, если макет используется в презентации (свойство HasDependingSlides истинно). |

### Заметки

1) Чтобы избежать выбрасывания PptxEditException, проверьте свойство HasDependingSlides макета заранее. 2) Вы также можете использовать метод [`Remove`](../../ilayoutslide/remove) для упрощения кода.

### См. Также

* интерфейс [IMasterLayoutSlideCollection](../../imasterlayoutslidecollection)
* пространство имен [Aspose.Slides](../../imasterlayoutslidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->