---
title: ToXmlString()
second_title: Aspose.Slides für C++ API-Referenz
description: Exportiert alle Parameter im XML-Format. Nicht implementiert.
type: docs
weight: 157
url: /de/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) Methode


Exportiert alle Parameter im XML-Format. Nicht implementiert.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| include_private_parameters | **bool** | True, um sowohl private als auch öffentliche Parameter zu exportieren, false, um nur öffentliche Parameter zu exportieren. |

### Rückgabewert

XML-kodierte Parameter.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) Methode


Exportiert alle Parameter im XML-Format.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | Format der resultierenden XML-Zeichenfolge. |

### Rückgabewert

XML-kodierte Parameter.

## Siehe auch

* Aufzählung [ECKeyXmlFormat](../../eckeyxmlformat/)
* Klasse [String](../../../system/string/)
* Klasse [ECDsaBotan](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)