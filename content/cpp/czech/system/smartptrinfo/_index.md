---
title: SmartPtrInfo
second_title: Aspose.Slides pro C++ referenční příručka API
description: Služební třída pro testování a úpravu obsahu SmartPtr bez znalosti konečného typu. Používá se pro garbage collection a detekci cyklických odkazů atd. Považujte ji za 'pointer to pointer'. Nemůžeme použít basetype SmartPtr, protože žádný nemá; místo toho používáme tuto 'info' třídu.
type: docs
weight: 1249
url: /cs/system/smartptrinfo/
---
## SmartPtrInfo třída


Služební třída pro testování a úpravu [SmartPtr](../smartptr/)'s contents bez znalosti konečného typu. Používá se pro garbage collection a loop references detection, atd. Považujte ji za „pointer to pointer“. Nemůžeme použít [SmartPtr](../smartptr/)'s basetype, protože žádný nemá; místo toho používáme tuto „info“ třídu.

```cpp
class SmartPtrInfo
```

## Metody

| Metoda | Popis |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Získá surový objekt, na který ukazatel odkazuje. |
| [Object](../object/) * [getObject](./getobject/)() const | Získá objekt, na který ukazatel odkazuje. |
| [Object](../object/) * [getOwned](./getowned/)() const | Získá ukazatel na vlastněný objekt. |
|  [operator bool](./operator_bool/)() const | Kontroluje, zda objekt info ukazuje na nenulový ukazatel. |
| **bool** [operator!](./operator_not/)() const | Kontroluje, zda objekt info neukazuje na nenulový ukazatel. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Umožňuje volat metody [Object](../object/) ukazovaného odkazovaným ukazatelem. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Porovnává hodnoty ukazatelů odkazovaných dvěma objekty info. |
|  [SmartPtrInfo](./smartptrinfo/)() | Vytvoří prázdný [SmartPtrInfo](./) objekt. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Vytvoří [SmartPtrInfo](./) objekt s informacemi o konkrétním smart pointer. |
## Viz také

* jmenný prostor [System](../)
* Library [Aspose.Slides](../../)