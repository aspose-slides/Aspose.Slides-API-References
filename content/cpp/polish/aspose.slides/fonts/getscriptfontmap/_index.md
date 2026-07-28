---
title: GetScriptFontMap()
second_title: Aspose.Slides dla referencji API C++
description: Zwraca słownik wszystkich definicji czcionek skryptowych w prezentacji.
type: docs
weight: 79
url: /pl/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() metoda


Zwraca słownik wszystkich definicji czcionek skryptowych w prezentacji.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
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
* Klasa [Fonts](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)