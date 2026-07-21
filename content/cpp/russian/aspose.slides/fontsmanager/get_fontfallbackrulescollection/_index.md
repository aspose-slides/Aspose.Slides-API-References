---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides для C++ API Справочник
description: Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью корректной подстановки посредством функции fallback. Читайте IFontFallBackRulesCollection.
type: docs
weight: 27
url: /ru/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() метод

Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью корректной подстановки посредством функции fallback. Читать [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Примечания

```cpp
auto pres = MakeObject<Presentation>();
// Получение пустой или предварительно инициализированной коллекции правил из FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Добавление правил в коллекцию
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// или
// Инициализация нового экземпляра коллекции правил
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Добавление правил в коллекцию
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// И замена существующей коллекции новой в FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)