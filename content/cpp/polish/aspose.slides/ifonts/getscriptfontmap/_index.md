---
title: GetScriptFontMap()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca słownik wszystkich definicji czcionek skryptowych w prezentacji.
type: docs
weight: 79
url: /pl/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() metoda

Zwraca słownik wszystkich definicji czcionek skryptowych w prezentacji.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```

### Wartość zwracana

Słownik mapujący kody skryptów na nazwy czcionek.
## Uwagi




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDictionary](../../../system.collections.generic/idictionary/)
* Klasa [String](../../../system/string/)
* Klasa [IFonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)