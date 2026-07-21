---
title: IndexOf()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает индекс указанного правила в коллекции.
type: docs
weight: 157
url: /ru/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) метод


Возвращает индекс указанного правила в коллекции.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Имя шрифта для поиска. |

### Возвращаемое значение

Индекс шрифта или -1, если шрифт не найден в списке.
## Замечания



```cpp
// Создайте правило, содержащее список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Получить индекс Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## См. также

* Класс [String](../../../system/string/)
* Класс [FontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)