---
title: GetScriptFont()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de naam van het lettertype op dat is gekoppeld aan een specifieke scripttag van het presentatiethema.
type: docs
weight: 92
url: /nl/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) methode

Haalt de naam van het lettertype op dat is gekoppeld aan een specifieke scripttag van het presentatiethema.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | De BCP-47 scriptcode (bijv. "Latn", "Cyrl", "Jpan") die wordt gebruikt om een schrijfsysteem te identificeren. |

### Retourwaarde

De naam van het gebruikte lettertype voor het opgegeven script, of **null** indien het script niet is gedefinieerd.

## Opmerkingen

Dit voorbeeld toont hoe het lettertype dat is toegewezen aan het Cyrillische script in het presentatiethema kan worden opgehaald.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [Fonts](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)