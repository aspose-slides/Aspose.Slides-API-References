---
title: Remove()
second_title: Aspose.Slides для C++ справки по API
description: Удаляет первое вхождение конкретного правила FallBack из коллекции.
type: docs
weight: 53
url: /ru/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) метод

Удаляет первое вхождение конкретного правила FallBack из коллекции.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Правило, которое нужно удалить из коллекции. |

## Замечания

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IFontFallBackRule](../../ifontfallbackrule/)
* Класс [FontFallBackRulesCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)