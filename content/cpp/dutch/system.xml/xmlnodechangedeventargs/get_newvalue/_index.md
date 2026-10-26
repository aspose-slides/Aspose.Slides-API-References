---
title: get_NewValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de nieuwe waarde van het knooppunt.
type: docs
weight: 66
url: /nl/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() methode

Retourneert de nieuwe waarde van het knooppunt.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Retourwaarde

De nieuwe waarde van het knooppunt. Deze methode retourneert **nullptr** als het knooppunt geen attribuut of een tekstknooppunt is, of als het knooppunt wordt verwijderd. Als het wordt aangeroepen in een **XmlDocument::NodeChanging** event, **get_NewValue** retourneert de waarde van het knooppunt als de wijziging succesvol is. Als het wordt aangeroepen in een **XmlDocument::NodeChanged** event, **get_NewValue** retourneert de huidige waarde van het knooppunt.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeChangedEventArgs](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)