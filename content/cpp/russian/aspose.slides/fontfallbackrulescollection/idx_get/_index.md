---
title: idx_get()
second_title: Справка API Aspose.Slides для C++
description: Получает правило по указанному индексу. Только для чтения IFontFallBackRule.
type: docs
weight: 66
url: /ru/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) метод

Получает правило по указанному индексу. Только для чтения [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IFontFallBackRule](../../ifontfallbackrule/)
* Класс [FontFallBackRulesCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)