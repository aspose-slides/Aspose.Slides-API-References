---
title: MakeRelativeUri()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt het verschil tussen de URI's die door het huidige en het opgegeven Uri-object worden weergegeven.
type: docs
weight: 352
url: /nl/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) methode


Bepaalt het verschil tussen URI's die worden weergegeven door het huidige en het opgegeven [Uri](../) object.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De te vergelijken |

### Retourwaarde

Als de hostnaam en het schema van de door het huidige object en **toUri** vertegenwoordigde URI's hetzelfde zijn, retourneert deze methode een relatieve [Uri](../) die, wanneer toegevoegd aan de huidige URI-instantie, **toUri** oplevert. Als de hostnaam of het schema verschillend is, retourneert deze methode een [Uri](../) object dat de **uri** parameter representeert.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Uri](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)