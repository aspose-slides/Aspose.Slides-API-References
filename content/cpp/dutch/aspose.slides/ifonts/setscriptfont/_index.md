---
title: SetScriptFont()
second_title: Aspose.Slides voor C++ API-referentie
description: Wijst een fontnaam toe aan een specifiek scripttag, die bepaalt hoe tekst van dat script in de presentatie wordt weergegeven.
type: docs
weight: 105
url: /nl/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) method

Wijs een fontnaam toe aan een specifiek scripttag, die bepaalt hoe tekst van dat script wordt weergegeven in de presentatie.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | De BCP-47 scriptcode (bijv. "Arab", "Hebr", "Hans") die het schrijfsysteem identificeert. |
| fontName | [System::String](../../../system/string/) | De naam van het font dat aan het opgegeven script moet worden toegewezen. |
## Opmerkingen

Dit voorbeeld laat zien hoe je het font voor het Arabische script instelt op "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IFonts](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)