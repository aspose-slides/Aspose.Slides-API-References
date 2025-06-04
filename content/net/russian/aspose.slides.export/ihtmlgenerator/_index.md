---
title: IHtmlGenerator
second_title: Aspose.Sildes для .NET API Справочник
description: Генератор Html.
type: docs
weight: 3790
url: /ru/aspose.slides.export/ihtmlgenerator/
---

## Интерфейс IHtmlGenerator

Генератор Html.

```csharp
public interface IHtmlGenerator
```

## Свойства

| Название | Описание |
| --- | --- |
| [NextSlideIndex](../../aspose.slides.export/ihtmlgenerator/nextslideindex) { get; } | Возвращает индекс слайда, который будет отрендерен после текущего слайда, или -1, если в данный момент рендерится последний слайд. Только для чтения Int32. |
| [PreviousSlideIndex](../../aspose.slides.export/ihtmlgenerator/previousslideindex) { get; } | Возвращает индекс ранее отрендеренного слайда или -1, если рендерится первый слайд. Только для чтения Int32. |
| [SlideImageSize](../../aspose.slides.export/ihtmlgenerator/slideimagesize) { get; } | Возвращает размер изображения слайда. Только для чтения SizeF. |
| [SlideImageSizeUnit](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunit) { get; } | Возвращает единицу измерения, в которой указан размер изображения слайда. Только для чтения [`SvgCoordinateUnit`](../svgcoordinateunit). |
| [SlideImageSizeUnitCode](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunitcode) { get; } | Возвращает CSS код единицы, в которой указан размер изображения слайда. Только для чтения String. |
| [SlideIndex](../../aspose.slides.export/ihtmlgenerator/slideindex) { get; } | Возвращает индекс текущего слайда для рендеринга. Только для чтения Int32. |

## Методы

| Название | Описание |
| --- | --- |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue)(char[]) | Кавычит значение атрибута и добавляет его в HTML файл. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_2)(string) | Кавычит значение атрибута и добавляет его в HTML файл. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_1)(char[], int, int) | Кавычит значение атрибута и добавляет его в HTML файл. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml)(char[]) | Добавляет форматированный HTML текст. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_2)(string) | Добавляет форматированный HTML текст. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_1)(char[], int, int) | Добавляет форматированный HTML текст. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext)(char[]) | Добавляет простой текст в HTML файлы, заменяя специальные символы на HTML сущности. Переносы строк и пробелы не заменяются. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_2)(string) | Добавляет простой текст в HTML файлы, заменяя специальные символы на HTML сущности. Переносы строк и пробелы не заменяются. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_1)(char[], int, int) | Добавляет простой текст в HTML файлы, заменяя специальные символы на HTML сущности. Переносы строк и пробелы не заменяются. |

### Также см.  

* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->