---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides для C++ справочник API
description: Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью правильных замен с помощью функции fallback. Записать IFontFallBackRulesCollection.
type: docs
weight: 40
url: /ru/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) метод


Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью правильной замены посредством функции fallback. Записать [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Примечания



```cpp
auto pres = MakeObject<Presentation>();
// Получение пустой или предварительно инициализированной коллекции правил из FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// добавление правил в коллекцию
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// или
// инициализация нового экземпляра коллекции правил
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// добавление правил в коллекцию
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// и замена существующей коллекции новой в FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)