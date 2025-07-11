---
title: ISmartArtNode
second_title: Aspose.Sildes для .NET API Reference
description: Представляет узел диаграммы SmartArt.
type: docs
weight: 10240
url: /ru/aspose.slides.smartart/ismartartnode/
---

## Интерфейс ISmartArtNode

Представляет узел диаграммы SmartArt.

```csharp
public interface ISmartArtNode
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BulletFillFormat](../../aspose.slides.smartart/ismartartnode/bulletfillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для пули узла. Примечание: может вернуть null для определенных типов макетов SmartArt, которые не предоставляют пули для узлов. Только для чтения [`IFillFormat`](../../aspose.slides/ifillformat). |
| [ChildNodes](../../aspose.slides.smartart/ismartartnode/childnodes) { get; } | Возвращает коллекцию всех дочерних узлов текущего узла. Только для чтения [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [IsAssistant](../../aspose.slides.smartart/ismartartnode/isassistant) { get; set; } | Возвращает или устанавливает узел как помощник. Чтение/запись Boolean. |
| [IsHidden](../../aspose.slides.smartart/ismartartnode/ishidden) { get; } | Возвращает true, если этот узел является скрытым узлом в модели данных. Только для чтения Boolean. |
| [Level](../../aspose.slides.smartart/ismartartnode/level) { get; } | Возвращает уровень вложенности узла. Только для чтения Int32. |
| [OrganizationChartLayout](../../aspose.slides.smartart/ismartartnode/organizationchartlayout) { get; set; } | Возвращает или устанавливает тип макета организационной диаграммы, связанный с текущим узлом. Чтение/запись [`OrganizationChartLayoutType`](../organizationchartlayouttype). |
| [Position](../../aspose.slides.smartart/ismartartnode/position) { get; set; } | Возвращает или устанавливает индекс на основе нуля позиции узла среди узлов-соседей. Чтение/запись Int32. |
| [Shapes](../../aspose.slides.smartart/ismartartnode/shapes) { get; } | Возвращает коллекцию всех фигур, связанных с узлом. Только для чтения [`ISmartArtShapeCollection`](../ismartartshapecollection). |
| [TextFrame](../../aspose.slides.smartart/ismartartnode/textframe) { get; } | Возвращает или устанавливает текст узла. Только для чтения [`ITextFrame`](../../aspose.slides/itextframe). |

## Методы

| Имя | Описание |
| --- | --- |
| [Remove](../../aspose.slides.smartart/ismartartnode/remove)() | Удаляет текущий узел. |

### См. также

* пространство имен [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->