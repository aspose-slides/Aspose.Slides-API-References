---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides для C++: справка API
description: Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown.
type: docs
weight: 248
url: /ru/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) метод

Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте Markdown.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Примечания

Это свойство определяет, являются ли последовательные пробелы:
* сохранёнными как обычные пробельные символы,
* чередующимися между обычными пробелами и неразрывными пробелами (**&nbsp;**),
* или полностью заменёнными (после первого) на **&nbsp;**, чтобы сохранить визуальное выравнивание в выводе Markdown.

Значение по умолчанию — [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/).

## См. также

* Перечисление [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Класс [MarkdownSaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)