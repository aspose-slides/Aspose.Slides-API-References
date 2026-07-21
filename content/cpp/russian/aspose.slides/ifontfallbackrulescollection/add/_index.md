---
title: Add()
second_title: Справка по API Aspose.Slides для C++
description: Добавьте новое правило FallBack в конец коллекции.
type: docs
weight: 14
url: /ru/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method

Добавьте новое правило FallBack в конец коллекции.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Аргументы

| Parameter | Type | Description |
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
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [IFontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)