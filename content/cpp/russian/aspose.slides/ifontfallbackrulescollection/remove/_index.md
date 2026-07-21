---
title: Remove()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет первое вхождение определённого правила FallBack из коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) метод

Removes the first occurrence of a specific FallBack rule from the collection.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Правило, которое нужно удалить из коллекции. |
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
//Удаление
rulesList->Remove(firstRule);
```

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IFontFallBackRule](../../ifontfallbackrule/)
* Класс [IFontFallBackRulesCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)