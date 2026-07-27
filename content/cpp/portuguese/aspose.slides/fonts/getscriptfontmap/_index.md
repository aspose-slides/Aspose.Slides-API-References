---
title: GetScriptFontMap()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um dicionário com todas as definições de fontes de script na apresentação.
type: docs
weight: 79
url: /pt/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() método


Retorna um dicionário com todas as definições de fontes de script na apresentação.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Valor de Retorno

Um dicionário que mapeia códigos de script para nomes de fontes.
## Observações




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)