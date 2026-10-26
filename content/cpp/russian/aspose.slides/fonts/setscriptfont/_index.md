---
title: SetScriptFont()
second_title: Aspose.Slides для справочника API C++
description: Назначает имя шрифта определённому тегу сценария, который определяет, как текст этого сценария будет отображаться в презентации.
type: docs
weight: 105
url: /ru/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) метод


Назначает имя шрифта определённому тегу сценария, который определяет, как текст этого сценария будет отображаться в презентации.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Код сценария BCP-47 (например, "Arab", "Hebr", "Hans"), определяющий систему письма. |
| fontName | [System::String](../../../system/string/) | Имя шрифта, который требуется назначить указанному сценарию. |
## Примечания



Этот пример показывает, как установить шрифт для арабского сценария в "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [Fonts](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)