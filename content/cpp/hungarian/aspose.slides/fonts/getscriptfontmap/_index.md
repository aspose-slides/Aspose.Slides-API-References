---
title: GetScriptFontMap()
second_title: Aspose.Slides C++ API referenciája
description: Visszaad egy szótárat, amely a bemutatóban lévő összes szkriptbetűtípus-definíciót tartalmazza.
type: docs
weight: 79
url: /hu/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() metódus


Visszaad egy szótárat, amely a bemutatóban lévő összes szkriptbetűtípus-definíciót tartalmazza.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Visszatérési érték

Egy szótár, amely a szkriptkódokat a betűtípusnevekre képezi le.
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
* Osztály [Fonts](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)