---
title: RemoveScriptFont()
second_title: Aspose.Slides voor C++ API Referentie
description: Verwijdert de lettertype-instelling die is gekoppeld aan een specifiek script-tag uit de lettertype-collectie van het thema.
type: docs
weight: 118
url: /nl/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) methode

Verwijdert de lettertype-instelling die is gekoppeld aan een specifiek script-tag uit de lettertype-collectie van het thema.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | De BCP-47 scriptcode waarvan de lettertype-instelling moet worden verwijderd. |
## Opmerkingen

Dit voorbeeld laat zien hoe u de lettertype-toewijzing voor het Hebreeuwse script verwijdert:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IFonts](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)