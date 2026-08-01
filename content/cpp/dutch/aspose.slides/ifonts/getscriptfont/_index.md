---
title: GetScriptFont()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de naam van het lettertype op dat is gekoppeld aan een specifieke script-tag uit het presentatiethema.
type: docs
weight: 92
url: /nl/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) methode


Haalt de naam van het lettertype op dat is gekoppeld aan een specifiek script-tag uit het presentatiethema.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | De BCP-47 scriptcode (bijv. "Latn", "Cyrl", "Jpan") die wordt gebruikt om een schrift te identificeren. |

### Retourwaarde

De naam van het lettertype dat wordt gebruikt voor het opgegeven script, of **null** als het script niet is gedefinieerd.
## Opmerkingen



Dit voorbeeld laat zien hoe je het aan het Cyrillische script toegewezen lettertype kunt ophalen in het presentatiethema. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IFonts](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)