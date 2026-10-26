---
title: GetScriptFontMap()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un diccionario de todas las definiciones de fuentes de script en la presentación.
type: docs
weight: 79
url: /es/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() método


Devuelve un diccionario de todas las definiciones de fuentes de script en la presentación.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### Valor devuelto

Un diccionario que asigna códigos de script a nombres de fuentes.
## Observaciones




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDictionary](../../../system.collections.generic/idictionary/)
* Clase [String](../../../system/string/)
* Clase [IFonts](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)