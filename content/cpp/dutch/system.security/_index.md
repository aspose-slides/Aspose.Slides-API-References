---
title: "System::Security"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 807
url: /nl/system.security/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Secure string, vertegenwoordigt tekst die vertrouwelijk moet blijven. Deze klasse ENCRYPTIE DE interne gegevens NIET. Objecten van deze klasse mogen alleen worden gealloceerd met de functie [System::MakeObject()](../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten kan veroorzaken. Wrap altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze door te geven aan functies als argument. |
| [SecureStringMarshal](./securestringmarshal/) | Collectie van methoden voor het alloceren en kopiëren van niet-beheerde geheugenblokken. |
| [SecurityElement](./securityelement/) | XML-objectmodel voor het coderen van beveiligingsobjecten. Niet geïmplementeerd. Objecten van deze klasse mogen alleen worden gealloceerd met de functie [System::MakeObject()](../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten kan veroorzaken. Wrap altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze door te geven aan functies als argument. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) pointer-type. |