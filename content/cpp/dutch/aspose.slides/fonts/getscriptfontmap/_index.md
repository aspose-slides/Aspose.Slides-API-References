---
title: GetScriptFontMap()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een woordenboek van alle scriptlettertype-definities in de presentatie.
type: docs
weight: 79
url: /nl/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() methode


Retourneert een woordenboek van alle scriptlettertype-definities in de presentatie.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Retourwaarde

Een woordenboek dat scriptcodes map naar lettertype-namen.
## Opmerkingen




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [Fonts](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)