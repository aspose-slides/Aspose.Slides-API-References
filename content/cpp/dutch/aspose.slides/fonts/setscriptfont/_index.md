---
title: SetScriptFont()
second_title: Aspose.Slides voor C++ API-referentie
description: Ken een lettertype-naam toe aan een specifiek script-tag, die bepaalt hoe tekst van dat script wordt weergegeven in de presentatie.
type: docs
weight: 105
url: /nl/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) methode


Ken een lettertype-naam toe aan een specifiek script-tag, die bepaalt hoe tekst van dat script wordt weergegeven in de presentatie.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | De BCP-47 scriptcode (bijv. \"Arab\", \"Hebr\", \"Hans\") die het schrijfsysteem identificeert. |
| fontName | [System::String](../../../system/string/) | De naam van het lettertype dat aan het opgegeven script wordt toegewezen. |
## Opmerkingen



Dit voorbeeld toont hoe het lettertype voor het Arabische script kan worden ingesteld op \"Segoe UI\": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [Fonts](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)