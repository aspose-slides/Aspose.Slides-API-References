---
title: SplitTextByColumns()
second_title: Справочник API Aspose.Slides для C++
description: Разбивает текстовое содержимое ITextFrame на массив строк,  где каждый элемент соответствует отдельному текстовому столбцу внутри кадра.
type: docs
weight: 118
url: /ru/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() метод

Разбивает текстовое содержимое [ITextFrame](../) на массив строк, 
 где каждый элемент соответствует отдельному текстовому столбцу внутри кадра.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### Возвращаемое значение

Массив строк, где каждая строка представляет текстовое содержимое конкретного столбца 
 в [ITextFrame](../).

## Примечания

Если текстовый кадр не содержит несколько столбцов, возвращаемый массив будет иметь один элемент 
 содержащий полный текст. 
 Пустые столбцы будут представлены пустыми строками в массиве. 
Следующий пример демонстрирует, как использовать [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Получить первую форму на слайде и привести её к ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Разбить содержимое текстового кадра на столбцы
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Вывести текст каждого столбца в консоль
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## См. также

* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [ITextFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)