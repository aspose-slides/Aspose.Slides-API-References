---
title: GetScriptFontMap()
second_title: Riferimento API di Aspose.Slides per C++ 
description: Restituisce un dizionario di tutte le definizioni di caratteri script nella presentazione.
type: docs
weight: 79
url: /it/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() metodo


Restituisce un dizionario di tutte le definizioni di caratteri script nella presentazione.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Valore di ritorno

Un dizionario che associa i codici script ai nomi dei caratteri.
## Osservazioni




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)