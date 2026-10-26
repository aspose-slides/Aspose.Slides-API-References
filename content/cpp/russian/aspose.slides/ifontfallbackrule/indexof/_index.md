---
title: IndexOf()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает индекс указанного правила в коллекции.
type: docs
weight: 118
url: /ru/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) метод

Возвращает индекс указанного правила в коллекции.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Имя шрифта для поиска. |

### Возвращаемое значение

Индекс шрифта или -1, если шрифт не найден в списке.

## Замечания

```cpp
// Создать правило, содержащий список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Получить индекс Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IFontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)