---
title: GetScriptFontMap()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy szótárat a prezentáció összes szkript betűtípus-definíciójáról.
type: docs
weight: 79
url: /hu/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() metódus


Visszaad egy szótárat a prezentáció összes szkript betűtípus-definíciójáról.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### Visszatérési érték

Egy szótár, amely a szkriptkódokat betűtípusnevekre képezi le.
## Megjegyzések




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IDictionary](../../../system.collections.generic/idictionary/)
* Osztály [String](../../../system/string/)
* Osztály [IFonts](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)