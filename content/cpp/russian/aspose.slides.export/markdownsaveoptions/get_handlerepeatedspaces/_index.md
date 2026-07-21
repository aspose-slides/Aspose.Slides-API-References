---
title: get_HandleRepeatedSpaces()
second_title: Справочник API Aspose.Slides для C++
description: Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown.
type: docs
weight: 235
url: /ru/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const метод

Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Примечания

Это свойство определяет, являются ли последовательные пробелы:
* сохранены как обычные пробельные символы,
* чередуются между обычными пробелами и неразрывными пробельными сущностями (**&nbsp;**),
* либо полностью заменяются (после первого) на **&nbsp;**, чтобы сохранить визуальное выравнивание в выводе Markdown.

Значение по умолчанию равно [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## См. также

* Перечисление [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Класс [MarkdownSaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)