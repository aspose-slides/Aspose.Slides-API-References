---
title: Equals()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt, ob die angegebene Region identisch ist mit der Region, die vom aktuellen Objekt auf der angegebenen Zeichenfläche dargestellt wird.
type: docs
weight: 157
url: /de/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) method


Ermittelt, ob die angegebene Region identisch ist mit der Region, die vom aktuellen Objekt auf der angegebenen Zeichenfläche dargestellt wird.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Die Region, mit der diese Region verglichen wird |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Eine Zeichenfläche |

### Rückgabewert

Wahr, wenn das Innere der angegebenen Region identisch ist mit dem Inneren der Region, die vom aktuellen Objekt repräsentiert wird, wenn die mit dem Parameter **g** verbundene Transformation angewendet wird; andernfalls – falsch

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Region](../)
* Klasse [Graphics](../../graphics/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)