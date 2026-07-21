---
title: AddFallBackFonts()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет новый шрифт(ы) в список шрифтов-замещения.
type: docs
weight: 79
url: /ru/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) метод


Добавляет новый шрифт(ы) в список шрифтов-замещения.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Имя шрифта или имена (разделённые запятыми) для FallBack |
## Примечания



```cpp
// Создать новый экземпляр FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Добавить второй шрифт к правилу
newRule->AddFallBackFonts(u"MS Gothic");
//Добавить третий и четвертый шрифты к правилу
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) метод


Добавляет новые шрифты в список шрифтов-замещения.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Имя шрифта или имена (разделённые запятыми) для FallBack |
## Примечания



```cpp
//Создать новый экземпляр FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Добавить ещё три шрифта к правилу
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [FontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)