---
title: idx_get()
second_title: Aspose.Slides для C++ справочника API
description: Получает правило по указанному индексу. Только для чтения IFontFallBackRule.
type: docs
weight: 1
url: /ru/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) метод

Получает правило по указанному индексу. Только для чтения [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Примечания

```cpp
auto pres = MakeObject<Presentation>();
//Получение пустой или предварительно инициализированной коллекции правил из FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Добавление нескольких правил в коллекцию
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Получение объекта первого правила в коллекции
auto firstRule = rulesList->idx_get(0);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IFontFallBackRule](../../ifontfallbackrule/)
* Класс [IFontFallBackRulesCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)