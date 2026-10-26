---
title: RemoveScriptFont()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de lettertype-instelling die gekoppeld is aan een specifiek script-tag uit de lettertypecollectie van het thema.
type: docs
weight: 118
url: /nl/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) methode


Verwijdert de lettertype-instelling die aan een specifiek script-tag is gekoppeld uit de lettertypecollectie van het thema.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | De BCP-47 scriptcode waarvan de lettertype-instelling moet worden verwijderd. |
## Opmerkingen



Dit voorbeeld laat zien hoe u de lettertype-toewijzing voor het Hebreeuwse script kunt verwijderen: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [Fonts](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)