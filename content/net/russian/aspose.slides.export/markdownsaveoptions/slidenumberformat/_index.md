---
title: SlideNumberFormat
second_title: Aspose.Sildes для .NET API Справочник
description: Получает или задает строку формата, используемую для заголовков номера слайда в выводе Markdown. Формат должен включать заполнитель 0, который будет заменен на индекс слайда во время экспорта. Например,  Slide 0 будет производить Slide 1, Slide 2 и т.д.
type: docs
weight: 120
url: /ru/aspose.slides.export/markdownsaveoptions/slidenumberformat/
---

## Свойство MarkdownSaveOptions.SlideNumberFormat

Получает или задает строку формата, используемую для заголовков номера слайда в выводе Markdown. Формат должен включать заполнитель "{0}", который будет заменен на индекс слайда во время экспорта. Пример: "# Slide {0}" будет производить "# Slide 1", "# Slide 2" и т.д.

```csharp
public string SlideNumberFormat { get; set; }
```

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Генерируется, если предоставленное значение равно null или пустое. |
| ArgumentException | Генерируется, если строка формата не содержит заполнитель "{0}". |

### Также смотри

* класс [MarkdownSaveOptions](../../markdownsaveoptions)
* пространство имен [Aspose.Slides.Export](../../markdownsaveoptions)
* сборка [Aspose.Slides](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.Slides.dll -->
