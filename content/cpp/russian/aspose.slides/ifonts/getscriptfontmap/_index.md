---
title: GetScriptFontMap()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает словарь всех определений шрифтов скриптов в презентации.
type: docs
weight: 79
url: /ru/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() метод

Возвращает словарь всех определений шрифтов скриптов в презентации.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```

### Возвращаемое значение

Словарь, сопоставляющий коды скриптов с именами шрифтов.

## Примечания

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDictionary](../../../system.collections.generic/idictionary/)
* Класс [String](../../../system/string/)
* Класс [IFonts](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)