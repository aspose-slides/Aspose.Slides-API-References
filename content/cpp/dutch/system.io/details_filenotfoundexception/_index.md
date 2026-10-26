---
title: Details_FileNotFoundException
second_title: Aspose.Slides voor C++ API-referentie
description: "De uitzondering die wordt gegooid wanneer een poging wordt gedaan om een bestand te openen dat niet bestaat op de schijf, mislukt. Maak nooit handmatig exemplaren van deze klasse. Gebruik in plaats daarvan de klasse FileNotFoundException. Wrap nooit de exemplaren van de klasse FileNotFoundException in System::SmartPtr."
type: docs
weight: 183
url: /nl/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException klasse


De uitzondering die wordt gegooid wanneer een poging om een bestand te openen dat niet bestaat op de schijf, mislukt. Maak nooit handmatig exemplaren van deze klasse. Gebruik in plaats daarvan de klasse FileNotFoundException. Wrap nooit de exemplaren van de klasse FileNotFoundException in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Haalt de naam van het bestand op dat deze uitzondering veroorzaakt. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |
## Zie ook

* Klasse [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)