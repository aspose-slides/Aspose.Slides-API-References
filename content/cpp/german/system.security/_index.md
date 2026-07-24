---
title: "System::Security"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 807
url: /de/system.security/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Sicherer String, stellt Text dar, der vertraulich behandelt werden soll. Diese Klasse VERSCHLÜSSELT die internen Daten NICHT. Objekte dieser Klasse dürfen nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SecureStringMarshal](./securestringmarshal/) | Sammlung von Methoden zum Allozieren und Kopieren von nicht verwalteten Speicherblöcken. |
| [SecurityElement](./securityelement/) | XML-Objektmodell für die Codierung von Sicherheitsobjekten. Nicht implementiert. Objekte dieser Klasse dürfen nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) Zeigertyp. |