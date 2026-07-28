---
title: ToXmlString()
second_title: Aspose.Slides C++ API referenciája
description: Az összes paramétert XML formátumban exportálja. Nincs megvalósítva.
type: docs
weight: 157
url: /hu/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) metódus

Az összes paramétert XML formátumban exportálja. Nincs megvalósítva.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| include_private_parameters | **bool** | True, ha a privát és nyilvános paramétereket is exportálni kell, false, ha csak a nyilvános paramétereket kell exportálni. |

### Visszatérési érték

XML-kódolt paraméterek.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) metódus

Az összes paramétert XML formátumban exportálja.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | Az eredmény XML karakterlánc formátuma. |

### Visszatérési érték

XML-kódolt paraméterek.

## Lásd még

* Enum [ECKeyXmlFormat](../../eckeyxmlformat/)
* Osztály [String](../../../system/string/)
* Osztály [ECDsaBotan](../)
* Névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)