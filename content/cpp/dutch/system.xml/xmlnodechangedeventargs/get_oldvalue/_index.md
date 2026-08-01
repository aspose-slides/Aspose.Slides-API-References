---
title: get_OldValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de oorspronkelijke waarde van het knooppunt.
type: docs
weight: 53
url: /nl/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() methode


Retourneert de oorspronkelijke waarde van het knooppunt.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Retourwaarde

De oorspronkelijke waarde van het knooppunt. Deze methode retourneert **nullptr** als het knooppunt noch een attribuut noch een tekstknooppunt is, of als het knooppunt wordt ingevoegd. Als het wordt aangeroepen in een **XmlDocument::NodeChanging** evenement, retourneert **get_OldValue** de huidige waarde van het knooppunt die zal worden vervangen als de wijziging succesvol is. Als het wordt aangeroepen in een **XmlDocument::NodeChanged** evenement, retourneert **get_OldValue** de waarde van het knooppunt vóór de wijziging.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeChangedEventArgs](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)