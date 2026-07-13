---
title: IMasterSlideCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje kolekci hlavních snímků.
type: docs
url: /cs/com.aspose.slides/imasterslidecollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Reprezentuje kolekci hlavních snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Odstraní první výskyt specifického objektu z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu kolekce. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Odstraní nepoužité hlavní snímky. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Přidá kopii určeného hlavního snímku na konec kolekce. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Vloží kopii určeného hlavního snímku na určenou pozici v kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Odstraní první výskyt specifického objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek, který má být z kolekce odstraněn. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na zadaném indexu kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový (zero-based) index prvku, který má být odstraněn. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Odstraní nepoužité hlavní snímky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| ignorePreserveField | boolean | Určuje, zda by tato metoda měla odstranit nepoužité hlavní snímky i když je její [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) vlastnost nastavena na true. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Přidá kopii určeného hlavního snímku na konec kolekce. Propojené snímky rozvržení budou také zkopírovány.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Snímek ke klonování. |

**Návratová hodnota:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Přidaný snímek.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Vloží kopii určeného hlavního snímku na určenou pozici v kolekci. Propojené snímky rozvržení budou také zkopírovány.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Snímek ke klonování. |

**Návratová hodnota:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Vložený hlavní snímek.