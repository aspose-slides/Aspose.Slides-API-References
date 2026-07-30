---
title: Equals()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje, zda je zadaný region identický s regionem představovaným aktuálním objektem na určeném kreslicím povrchu.
type: docs
weight: 157
url: /cs/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) metoda

Určuje, zda je zadaný region identický s regionem představovaným aktuálním objektem na zadaném kreslicím povrchu.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Region, se kterým se porovnává tento region |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Kreslicí povrch |

### Návratová hodnota

True, pokud je vnitřek zadaného regionu identický s vnitřkem regionu představovaného aktuálním objektem, když je použita transformace spojená s parametrem **g**; jinak - false

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Region](../)
* Třída [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)