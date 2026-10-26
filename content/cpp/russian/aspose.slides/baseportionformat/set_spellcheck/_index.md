---
title: set_SpellCheck()
second_title: Aspose.Slides для C++ Справочник API
description: Устанавливает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство установлено в false, проверка орфографии для текстовых элементов подавляется. При установке в true проверка орфографии разрешена. Значение по умолчанию — false.
type: docs
weight: 612
url: /ru/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) метод

Устанавливает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство установлено в false, проверка орфографии для текстовых элементов подавляется. При установке в true проверка орфографии разрешена. Значение по умолчанию — **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Примечания

В следующем примере демонстрируется включение флага SpellCheck перед сохранением презентации:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Класс [BasePortionFormat](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)