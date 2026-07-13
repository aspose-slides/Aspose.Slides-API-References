---
title: IMasterSlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling master slides voor.
type: docs
url: /nl/com.aspose.slides/imasterslidecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Stelt een verzameling master slides voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Removes unused master slides. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified master slide to the end of the collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserts a copy of a specified master slide to specified position of the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Verwijdert de eerste verschijning van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | De master slide die uit de collectie moet worden verwijderd. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Verwijdert ongebruikte master slides.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ignorePreserveField | boolean | Bepaalt of deze methode ongebruikte masters moet verwijderen, zelfs als de [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-)-eigenschap op true is ingesteld. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Voegt een kopie van een opgegeven master slide toe aan het einde van de collectie. Gekoppelde layout slides worden ook gekopieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide om te klonen. |

**Retourwaarde:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Toegevoegde slide.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Voegt een kopie van een opgegeven master slide in op een specifieke positie in de collectie. Gekoppelde layout slides worden ook gekopieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe slide. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide om te klonen. |

**Retourwaarde:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Ingevoegde master slide.