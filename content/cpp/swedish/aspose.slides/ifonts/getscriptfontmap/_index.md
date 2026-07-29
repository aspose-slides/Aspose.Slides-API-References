---
title: GetScriptFontMap()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ordbok med alla skriptfontdefinitioner i presentationen.
type: docs
weight: 79
url: /sv/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() method


Returnerar en ordbok med alla skriptfontdefinitioner i presentationen.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
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
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IFonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)