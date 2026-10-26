---
title: FontFallBackRule()
second_title: Aspose.Slides для C++ API Reference
description: Создаёт новый экземпляр.
type: docs
weight: 66
url: /ru/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) конструктор


Создает новый экземпляр.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **uint32_t** | Начальный индекс диапазона unicode |
| endIndex | **uint32_t** | Конечный индекс диапазона unicode |
| fontNames | [System::String](../../../system/string/) | Имя (или имена) шрифта (разделённые запятыми) для FallBack |
## Примечания



```cpp
// Создайте новый экземпляр FantFallBackRule с одним шрифтом.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Создайте новый экземпляр FantFallBackRule с несколькими шрифтами.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) конструктор


Создает новый экземпляр.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **uint32_t** | Начальный индекс диапазона unicode |
| endIndex | **uint32_t** | Конечный индекс диапазона unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Имя (или имена) шрифта (разделённые запятыми) для FallBack |
## Примечания



```cpp
// Создайте новый экземпляр FantFallBackRule с двумя шрифтами
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Создайте новый экземпляр FantFallBackRule с несколькими шрифтами.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [FontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)