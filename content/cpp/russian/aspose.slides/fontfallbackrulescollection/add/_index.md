---
title: Add()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет указанное правило FallBack в конец коллекции.
type: docs
weight: 40
url: /ru/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) метод

Добавляет указанное правило FallBack в конец коллекции.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Указанное правило для добавления |
## Примечания

```cpp
auto pres = MakeObject<Presentation>();
//Получение пустой или предварительно инициализированной коллекции правил из FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Добавление нового правила в коллекцию
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IFontFallBackRule](../../ifontfallbackrule/)
* Класс [FontFallBackRulesCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)