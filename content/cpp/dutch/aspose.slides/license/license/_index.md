---
title: License()
second_title: Aspose.Slides voor C++ API Referentie
description: Initialiseert een nieuwe instantie van deze klasse.
type: docs
weight: 1
url: /nl/aspose.slides/license/license/
---
## License::License() constructor


Initialiseert een nieuwe instantie van deze klasse.

```cpp
Aspose::Slides::License::License()
```

## Opmerkingen


In dit voorbeeld wordt geprobeerd een licentiebestand genaamd MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde bronnen van de aanroepende assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Zie ook

* Klasse [License](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)