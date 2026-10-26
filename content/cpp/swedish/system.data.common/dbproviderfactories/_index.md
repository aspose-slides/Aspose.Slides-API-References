---
title: DbProviderFactories
second_title: Aspose.Slides för C++ API-referens
description: "API för att hämta DB-leverantörsfabriker. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Kapsla alltid in denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 53
url: /sv/system.data.common/dbproviderfactories/
---
## DbProviderFactories klass

API för att hämta DB-leverantörsfabriker. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Kapsla alltid in denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att vidarebefordra den till funktioner som argument.

```cpp
class DbProviderFactories
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Hämtar DB-leverantörsfabrik efter namn. |
## Se även

* Namnrymd [System::Data::Common](../)
* Bibliotek [Aspose.Slides](../../)