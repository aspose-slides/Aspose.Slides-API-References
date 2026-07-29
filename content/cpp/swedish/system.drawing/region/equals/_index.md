---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om den angivna regionen är identisk med den region som representeras av det aktuella objektet på den angivna ritytan.
type: docs
weight: 157
url: /sv/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) method


Bestämmer om den angivna regionen är identisk med den region som representeras av det aktuella objektet på den angivna ritytan.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Regionen att jämföra denna region med |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | En rityta |

### Returvärde

True om inre av den angivna regionen är identiskt med inre av regionen som representeras av det aktuella objcet när transformationen som är associerad med **g**-parametern tillämpas; annars - false

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Region](../)
* Klass [Graphics](../../graphics/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)