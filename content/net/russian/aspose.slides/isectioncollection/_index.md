---
title: ISectionCollection
second_title: Aspose.Slides для .NET API Reference
description: Представляет коллекцию разделов.
type: docs
weight: 6700
url: /ru/aspose.slides/isectioncollection/
---

## Интерфейс ISectionCollection

Представляет коллекцию разделов.

```csharp
public interface ISectionCollection : IGenericCollection<ISection>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides/isectioncollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения [`ISection`](../isection). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEmptySection](../../aspose.slides/isectioncollection/addemptysection)(string, int) | Добавляет пустой раздел в указанную позицию коллекции. |
| [AddSection](../../aspose.slides/isectioncollection/addsection)(string, ISlide) | Добавляет новый раздел, начинающийся с указанного слайда. |
| [AppendEmptySection](../../aspose.slides/isectioncollection/appendemptysection)(string) | Добавляет пустой раздел в конец коллекции. |
| [Clear](../../aspose.slides/isectioncollection/clear)() | Удаляет все разделы из коллекции. |
| [IndexOf](../../aspose.slides/isectioncollection/indexof)(ISection) | Возвращает индекс указанного раздела в коллекции. |
| [RemoveSection](../../aspose.slides/isectioncollection/removesection)(ISection) | Удаляет раздел. Слайды, содержащиеся в разделе, будут объединены с предыдущим разделом. |
| [RemoveSectionWithSlides](../../aspose.slides/isectioncollection/removesectionwithslides)(ISection) | Удаляет раздел и слайды, содержащиеся в разделе. |
| [ReorderSectionWithSlides](../../aspose.slides/isectioncollection/reordersectionwithslides)(ISection, int) | Перемещает раздел и его слайды из коллекции в указанную позицию. |

### Смотрите также

* интерфейс [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* интерфейс [ISection](../isection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->