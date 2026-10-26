---
title: AddFallBackFonts()
second_title: Aspose.Slides для C++ справка API
description: Добавляет новый шрифт(ы) в список шрифтов FallBack.
type: docs
weight: 40
url: /ru/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) метод

Добавляет новый шрифт(ы) в список шрифтов FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Имя или имена шрифтов (разделённые запятыми) для FallBack |
## Примечания

```cpp
//Создание нового экземпляра FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Добавить второй шрифт к правилу
newRule->AddFallBackFonts(u"MS Gothic");
//Добавить третий и четвертый шрифты к правилу
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) метод

Добавляет новые шрифты в список шрифтов FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Имя или имена шрифтов (разделённые запятыми) для FallBack |
## Примечания

```cpp
//Создание нового экземпляра FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Добавление ещё трёх шрифтов к правилу
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [IFontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)