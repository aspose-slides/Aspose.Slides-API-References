---
title: ISummaryZoomSectionCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию объектов Summary Zoom Section.
type: docs
url: /ru/com.aspose.slides/isummaryzoomsectioncollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Представляет коллекцию объектов Summary Zoom Section.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Создаёт новый объект Summary Zoom Section и добавляет его в коллекцию |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Возвращает элемент Summary Zoom Section для указанного раздела. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Удаляет объект Summary Zoom Section из коллекции. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Возвращает индекс указанного объекта SummaryZoomSection. |
| [clear()](#clear--) | Удаляет все объекты SummaryZoomSection из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

Возвращает элемент по указанному индексу. Только для чтения [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

Создаёт новый объект Summary Zoom Section и добавляет его в коллекцию

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для нового элемента Summary Zoom Section [ISection](../../com.aspose.slides/isection)

Если элемент для этого раздела уже существует в коллекции, возвращается существующий элемент. |
**Возвращаемое значение:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Добавлен [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) элемент
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

Возвращает элемент Summary Zoom Section для указанного раздела.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для поиска [ISection](../../com.aspose.slides/isection) |

**Возвращаемое значение:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) или null, если коллекция не содержит элемент для раздела.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

Удалить объект Summary Zoom Section из коллекции.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Раздел, для которого элемент Summary Zoom Section должен быть удалён [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

Возвращает индекс указанного объекта SummaryZoomSection.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Объект SummaryZoomSection для поиска [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Возвращаемое значение:**
int - Индекс объекта SummaryZoomSection или -1, если объект SummaryZoomSection не принадлежит этой коллекции.
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все объекты SummaryZoomSection из коллекции.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```