---
title: Equals()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa, czy podany region jest identyczny z regionem reprezentowanym przez bieżący obiekt na określonej powierzchni rysunkowej.
type: docs
weight: 157
url: /pl/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) metoda

Określa, czy podany region jest identyczny z regionem reprezentowanym przez bieżący obiekt na określonej powierzchni rysunkowej.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Region, z którym porównywany jest ten region |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Powierzchnia rysunkowa |

### Wartość zwracana

True jeśli wnętrze określonego regionu jest identyczne z wnętrzem regionu reprezentowanego przez bieżący obiekt, gdy zastosowane zostanie przekształcenie powiązane z parametrem **g**; w przeciwnym razie - false

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)