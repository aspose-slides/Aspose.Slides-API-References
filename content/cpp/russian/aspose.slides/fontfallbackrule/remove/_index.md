---
title: Remove()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет первое вхождение конкретного шрифта FallBack из списка.
type: docs
weight: 118
url: /ru/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) метод

Удаляет первое вхождение конкретного шрифта FallBack из списка.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Имя шрифта, которое нужно удалить из списка. |
## Примечания

```cpp
// Создать правило, содержащее список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Удалить Tahoma из списка.
newRule->Remove(u"Tahoma");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [FontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)