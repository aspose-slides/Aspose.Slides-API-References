---
title: ToXmlString()
second_title: Aspose.Slides för C++ API-referens
description: Exporterar alla parametrar i XML-format. Ej implementerad.
type: docs
weight: 157
url: /sv/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) method

Exporterar alla parametrar i XML-format. Ej implementerad.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| include_private_parameters | **bool** | Sant för att exportera både privata och offentliga parametrar, falskt för att endast exportera offentliga parametrar. |

### Returvärde

XML-kodade parametrar.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) method

Exporterar alla parametrar i XML-format.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | Format för den resulterande XML-strängen. |

### Returvärde

XML-kodade parametrar.

## Se även

* Enum [ECKeyXmlFormat](../../eckeyxmlformat/)
* Klass [String](../../../system/string/)
* Klass [ECDsaBotan](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)