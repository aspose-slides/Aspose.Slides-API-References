---
title: GetScriptFontMap()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt ein Wörterbuch aller Skript-Schriftartdefinitionen in der Präsentation zurück.
type: docs
weight: 79
url: /de/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() Methode


Gibt ein Wörterbuch aller Skript-Schriftartdefinitionen in der Präsentation zurück.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Rückgabewert

Ein Wörterbuch, das Skriptcodes zu Schriftartnamen abbildet.
## Bemerkungen




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [Fonts](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)