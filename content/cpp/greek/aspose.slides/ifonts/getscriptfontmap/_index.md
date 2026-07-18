---
title: GetScriptFontMap()
second_title: Aspose.Slides για την Αναφορά API C++
description: Επιστρέφει ένα λεξικό με όλους τους ορισμούς γραμματοσειρών σεναρίου στην παρουσίαση.
type: docs
weight: 79
url: /el/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() μέθοδος


Επιστρέφει ένα λεξικό όλων των ορισμών γραμματοσειρών σεναρίου στην παρουσίαση.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### Τιμή επιστροφής

Ένα λεξικό που αντιστοιχίζει κώδικες σεναρίου σε ονόματα γραμματοσειρών.
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
* Κλάση [IFonts](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)