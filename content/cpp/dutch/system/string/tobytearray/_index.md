---
title: ToByteArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een string of deelstring naar een array van bytes.
type: docs
weight: 508
url: /nl/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const method


Converteert een string of deelstring naar een array van bytes.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Beginindex van de deelstring. |
| length | **int32_t** | Lengte van de deelstring. |
| LE | **bool** | Als true, codeer de tekens met little endianness; anders gebruik je big endianness. |

### Retourwaarde

[Array](../../array/) bevat bytes die de tekens van de string vertegenwoordigen.

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)