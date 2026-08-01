---
title: HexUnescape()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven hexadecimale representatie van een teken naar een teken.
type: docs
weight: 443
url: /nl/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) methode


Converteert de opgegeven hexadecimale representatie van een teken naar een teken.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Een string die de hexadecimale representatie van een teken bevat |
| index | **int32_t**\& | De positie in **pattern** waar de hexadecimale representatie van een teken begint |

### Retourwaarde

Het teken dat wordt vertegenwoordigd door de hexadecimale codering op positie **index**. Als het teken op **index** niet hexadecimaal gecodeerd is, wordt het teken op **index** geretourneerd. De waarde van **index** wordt verhoogd zodat deze naar het teken na het geretourneerde teken wijst.

## Zie ook

* Klasse [String](../../string/)
* Klasse [Uri](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)