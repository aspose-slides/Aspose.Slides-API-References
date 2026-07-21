---
title: GetScriptFontMap()
second_title: Aspose.Slides для C++ — справочник API
description: Возвращает словарь всех определений шрифтов скриптов в презентации.
type: docs
weight: 79
url: /ru/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() метод

Возвращает словарь всех определений шрифтов скриптов в презентации.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Возвращаемое значение

Словарь, сопоставляющий коды скриптов именам шрифтов.

## Примечания



```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDictionary](../../../system.collections.generic/idictionary/)
* Класс [String](../../../system/string/)
* Класс [Fonts](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)