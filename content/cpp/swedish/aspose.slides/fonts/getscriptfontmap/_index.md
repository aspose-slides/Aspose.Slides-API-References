---
title: GetScriptFontMap()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ordbok med alla skriptfontdefinitioner i presentationen.
type: docs
weight: 79
url: /sv/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() metod


Returnerar en ordbok med alla skriptfontdefinitioner i presentationen.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Returvärde

En ordbok som mappar skriptkoder till fontnamn.
## Anmärkningar




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDictionary](../../../system.collections.generic/idictionary/)
* Klass [String](../../../system/string/)
* Klass [Fonts](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)