---
title: GetScriptFontMap()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει ένα λεξικό με όλους τους ορισμούς γραμματοσειρών σεναρίου στην παρουσίαση.
type: docs
weight: 79
url: /el/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() μέθοδος


Επιστρέφει ένα λεξικό με όλους τους ορισμούς γραμματοσειρών σεναρίου στην παρουσίαση.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Τιμή Επιστροφής

Ένα λεξικό που αντιστοιχίζει κωδικούς σεναρίου σε ονόματα γραμματοσειρών.
## Παρατηρήσεις




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDictionary](../../../system.collections.generic/idictionary/)
* Κλάση [String](../../../system/string/)
* Κλάση [Fonts](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)