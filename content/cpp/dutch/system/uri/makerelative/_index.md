---
title: MakeRelative()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt het verschil tussen twee Uri-instanties.
type: docs
weight: 365
url: /nl/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) methode


Bepaalt het verschil tussen twee [Uri](../) instanties.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De URI om te vergelijken met de huidige URI |

### Retourwaarde

Als de hostnaam en het schema van de door het huidige object en **toUri** gerepresenteerde URI's hetzelfde zijn, retourneert deze methode een [String](../../string/) die een relatieve [Uri](../) vertegenwoordigt; wanneer toegevoegd aan de huidige URI-instantie, resulteert dit in **toUri**. Als de hostnaam of het schema verschillend is, retourneert deze methode een [String](../../string/) die de **uri**-parameter vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Uri](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)