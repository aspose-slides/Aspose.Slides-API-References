---
title: GetScriptFont()
second_title: Справочник API Aspose.Slides для C++
description: Получает имя шрифта, связанное с определённым тегом скрипта из темы презентации.
type: docs
weight: 92
url: /ru/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) метод

Gets the font name associated with a specific script tag from the presentation theme.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Код сценария BCP-47 (например, "Latn", "Cyrl", "Jpan"), используемый для идентификации системы письма. |

### Return Value

Имя шрифта, используемого для заданного сценария, или **null**, если сценарий не определён.

## Remarks

Этот пример демонстрирует, как получить шрифт, назначенный кириллическому сценарию в теме презентации. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## See Also

* Класс [String](../../../system/string/)
* Класс [Fonts](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)