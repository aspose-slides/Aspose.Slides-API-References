---
title: SplitTextByColumns()
second_title: Aspose.Slides для C++ справочника API
description: Разделяет текстовое содержимое ITextFrame на массив строк,  где каждый элемент соответствует отдельному текстовому столбцу внутри рамки.
type: docs
weight: 144
url: /ru/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() метод

Разделяет текстовое содержимое [ITextFrame](../../itextframe/) на массив строк, 

 где каждый элемент соответствует отдельному текстовому столбцу в рамке.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### Возвращаемое значение

Массив строк, где каждая строка представляет текстовое содержимое конкретного столбца 

 в [ITextFrame](../../itextframe/).

## Примечания

Если текстовая рамка не содержит несколько столбцов, возвращаемый массив будет содержать один элемент 

 содержащий весь текст. 

 Пустые столбцы будут представлены пустыми строками в массиве. 

Следующий пример демонстрирует, как использовать [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [TextFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)