---
title: ISectionCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет набор разделов.
type: docs
weight: 6340
url: /ru/net/aspose.slides/isectioncollection/
---
## ISectionCollection interface

Представляет набор разделов.

```csharp
public interface ISectionCollection : IGenericCollection<ISection>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides/isectioncollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения[`ISection`](../isection). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEmptySection](../../aspose.slides/isectioncollection/addemptysection)(string, int) | Добавить пустой раздел в указанную позицию коллекции. |
| [AddSection](../../aspose.slides/isectioncollection/addsection)(string, ISlide) | Добавить новый раздел, начинающийся с определенного слайда. |
| [AppendEmptySection](../../aspose.slides/isectioncollection/appendemptysection)(string) | Добавить пустой раздел в конец коллекции. |
| [Clear](../../aspose.slides/isectioncollection/clear)() | Удаляет все разделы из коллекции. |
| [IndexOf](../../aspose.slides/isectioncollection/indexof)(ISection) | Возвращает индекс указанного раздела в коллекции. |
| [RemoveSection](../../aspose.slides/isectioncollection/removesection)(ISection) | Удалить раздел. Слайды, содержащиеся в этом разделе, будут объединены с предыдущим разделом. |
| [RemoveSectionWithSlides](../../aspose.slides/isectioncollection/removesectionwithslides)(ISection) | Удалить раздел и слайды, содержащиеся в разделе. |
| [ReorderSectionWithSlides](../../aspose.slides/isectioncollection/reordersectionwithslides)(ISection, int) | Перемещает раздел и его слайды из коллекции в указанную позицию. |

### Смотрите также

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISection](../isection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->