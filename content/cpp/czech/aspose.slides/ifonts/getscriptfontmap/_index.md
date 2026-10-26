---
title: GetScriptFontMap()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací slovník všech definic skriptových fontů v prezentaci.
type: docs
weight: 79
url: /cs/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() method


Vrací slovník všech definic skriptových fontů v prezentaci.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### Návratová hodnota

Slovník mapující kódy skriptů na názvy fontů.
## Poznámky




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDictionary](../../../system.collections.generic/idictionary/)
* Třída [String](../../../system/string/)
* Třída [IFonts](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)