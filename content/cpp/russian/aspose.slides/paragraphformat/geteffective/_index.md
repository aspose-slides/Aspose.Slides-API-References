---
title: GetEffective()
second_title: Справочник API Aspose.Slides для C++
description: Получает эффективные данные форматирования абзаца с учётом наследования.
type: docs
weight: 365
url: /ru/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() метод

Получает эффективные данные форматирования абзаца с учётом наследования.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### Возвращаемое значение

A [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Примечания

Этот пример демонстрирует получение некоторых эффективных свойств формата абзаца. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Класс [ParagraphFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)