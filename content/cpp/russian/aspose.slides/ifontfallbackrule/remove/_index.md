---
title: Remove()
second_title: Aspose.Slides для C++: справка API
description: Удаляет первое вхождение конкретного шрифта FallBack из списка.
type: docs
weight: 79
url: /ru/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) метод

Удаляет первое вхождение конкретного шрифта FallBack из списка.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Имя шрифта, который нужно удалить из списка. |
## Примечания

```cpp
// Создаёт правило, содержащее список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Удаляем Tahoma из списка
newRule->Remove(u"Tahoma");
```

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [IFontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)