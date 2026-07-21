---
title: get_FontFallBackRulesCollection()
second_title: Справочник API Aspose.Slides для C++
description: Представляет пользовательскую коллекцию правил FontFallBack для управления коллекциями шрифтов и обеспечения правильных замен с помощью функции fallback. Читайте IFontFallBackRulesCollection.
type: docs
weight: 27
url: /ru/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() метод

Представляет пользовательскую коллекцию правил FontFallBack для управления коллекциями шрифтов и обеспечения правильных замен с помощью функции fallback. Читайте [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
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

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Класс [IFontsManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)