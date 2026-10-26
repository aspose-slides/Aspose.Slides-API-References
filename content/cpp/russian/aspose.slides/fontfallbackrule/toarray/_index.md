---
title: ToArray()
second_title: Справочник API Aspose.Slides для C++
description: Создает и возвращает массив со всеми FallBack шрифтами для этого правила.
type: docs
weight: 144
url: /ru/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() метод

Создает и возвращает массив со всеми FallBack шрифтами для этого правила.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Возвращаемое значение

Массив [System::String](../../../system/string/)

## Примечания

```cpp
// Создайте правило, содержащий список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Получите все имена шрифтов в виде массива.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) метод

Создает и возвращает массив со всеми FallBack шрифтами из указанного диапазона в списке.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
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
// Получите последние два имени шрифта в виде массива.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [FontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)