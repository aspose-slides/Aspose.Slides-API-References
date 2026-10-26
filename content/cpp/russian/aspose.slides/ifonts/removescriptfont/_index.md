---
title: RemoveScriptFont()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет настройку шрифта, связанную с конкретным тегом сценария, из коллекции шрифтов темы.
type: docs
weight: 118
url: /ru/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) метод


Removes the font setting associated with a specific script tag from the theme's font collection.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Код сценария BCP-47, для которого следует удалить настройку шрифта. |
## Примечания



Этот пример демонстрирует, как удалить сопоставление шрифта для еврейского сценария: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IFonts](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)