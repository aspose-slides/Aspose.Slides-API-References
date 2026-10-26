---
title: "System::Security"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 807
url: /sv/system.security/
---
## Klasser

| Class | Beskrivning |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Säker sträng, representerar text som bör hållas konfidentiell. Denna klass krypterar inte den interna datan. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller assertionsfel. Inslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [SecureStringMarshal](./securestringmarshal/) | Samling av metoder för att allokera och kopiera ohanterade minnesblock. |
| [SecurityElement](./securityelement/) | XML-objektmodell för kodning av säkerhetsobjekt. Inte implementerad. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller assertionsfel. Inslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) pekartyp. |