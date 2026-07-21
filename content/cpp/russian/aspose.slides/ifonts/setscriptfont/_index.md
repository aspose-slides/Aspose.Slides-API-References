---
title: SetScriptFont()
second_title: Aspose.Slides для справочника API C++
description: Назначает имя шрифта определенному тегу скрипта, который определяет, как будет отображаться текст этого скрипта в презентации.
type: docs
weight: 105
url: /ru/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) method

Назначает имя шрифта определенному тегу скрипта, который определяет, как будет отображаться текст этого скрипта в презентации.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Код скрипта BCP-47 (например, "Arab", "Hebr", "Hans"), идентифицирующий систему письма. |
| fontName | [System::String](../../../system/string/) | Имя шрифта, которое будет назначено указанному скрипту. |

## Примечания

В этом примере показано, как установить шрифт для арабского скрипта в "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IFonts](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)