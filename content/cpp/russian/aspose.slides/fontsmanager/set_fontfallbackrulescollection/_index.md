---
title: set_FontFallBackRulesCollection()
second_title: Справочник API Aspose.Slides для C++
description: Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью корректных замен с помощью функции резервного копирования Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /ru/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) метод

Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью корректных замен с помощью функции резервного копирования Записать [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
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

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Класс [FontsManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)