---
title: ToArray()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт и возвращает массив со всеми шрифтами FallBack для этого правила.
type: docs
weight: 105
url: /ru/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() метод


Создает и возвращает массив со всеми шрифтами FallBack для этого правила.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Возвращаемое значение

Массив [System::String](../../../system/string/)
## Примечания



```cpp
// Создайте правило, содержащий список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Получить все имена шрифтов как массив
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) метод


Создает и возвращает массив со всеми шрифтами FallBack из указанного диапазона в списке.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **int32_t** | Индекс первого шрифта для добавления. |
| count | **int32_t** | Количество шрифтов для добавления. |

### Возвращаемое значение

Массив [System::String](../../../system/string/)
## Примечания



```cpp
// Создайте правило, содержащий список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Получить два последних имени шрифта как массив
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [IFontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)