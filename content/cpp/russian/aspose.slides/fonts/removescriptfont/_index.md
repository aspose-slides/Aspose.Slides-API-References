---
title: RemoveScriptFont()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет настройку шрифта, связанную с конкретным тегом скрипта, из коллекции шрифтов темы.
type: docs
weight: 118
url: /ru/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) метод

Удаляет настройку шрифта, связанную с конкретным тегом скрипта, из коллекции шрифтов темы.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Код скрипта BCP-47, настройка шрифта которого должна быть удалена. |
## Примечания

Этот пример демонстрирует, как удалить сопоставление шрифта для еврейского скрипта:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [Fonts](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)