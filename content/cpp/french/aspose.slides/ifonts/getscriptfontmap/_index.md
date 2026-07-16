---
title: GetScriptFontMap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un dictionnaire de toutes les définitions de polices de script dans la présentation.
type: docs
weight: 79
url: /fr/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() méthode

Renvoie un dictionnaire de toutes les définitions de polices de script dans la présentation.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```

### Valeur de retour

Un dictionnaire associant les codes de script aux noms de polices.
## Remarques

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)