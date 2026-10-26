---
title: get_ParagraphFormat()
second_title: Aspose.Slides для справки API C++
description: Возвращает объект форматирования для этого абзаца. Только для чтения IParagraphFormat.
type: docs
weight: 14
url: /ru/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() метод

Возвращает объект форматирования для этого абзаца. Только для чтения [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Примечания

Объект форматирования содержит параметры форматирования, определённые только для текущего абзаца; унаследованные данные не применяются.

Чтобы получить эффективные значения, включая унаследованные, используйте метод [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IParagraphFormat](../../iparagraphformat/)
* Класс [Paragraph](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)