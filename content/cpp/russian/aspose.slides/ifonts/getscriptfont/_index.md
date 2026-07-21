---
title: GetScriptFont()
second_title: Справочник API Aspose.Slides для C++
description: Получает имя шрифта, связанное с конкретным тегом скрипта из темы презентации.
type: docs
weight: 92
url: /ru/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) метод

Получает имя шрифта, связанное с конкретным тегом скрипта из темы презентации.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Код скрипта BCP-47 (например, "Latn", "Cyrl", "Jpan"), используемый для идентификации системы письма. |

### Возвращаемое значение

Имя шрифта, используемого для указанного скрипта, или **null**, если скрипт не определён.

## Замечания

Этот пример демонстрирует, как получить шрифт, назначенный для кириллического скрипта в теме презентации. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## См. также

* Class [String](../../../system/string/)
* Class [IFonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)