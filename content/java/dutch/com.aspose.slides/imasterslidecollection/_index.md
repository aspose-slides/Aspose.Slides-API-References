---
title: IMasterSlideCollection
second_title: Aspose.Slides for Java API Referentie
description: Stelt een collectie van masterslides voor.
type: docs
url: /nl/com.aspose.slides/imasterslidecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Stelt een collectie van masterslides voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Verwijdert de eerste instantie van een specifiek object uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Verwijdert ongebruikte masterslides. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Voegt een kopie van een opgegeven masterslide toe aan het einde van de collectie. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Voegt een kopie van een opgegeven masterslide in op een opgegeven positie in de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Verwijdert de eerste instantie van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | De masterslide die uit de collectie moet worden verwijderd. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Verwijdert ongebruikte masterslides.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ignorePreserveField | boolean | Bepaalt of deze methode ongebruikte masters moet verwijderen zelfs als de [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) eigenschap op true staat. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Voegt een kopie van een opgegeven masterslide toe aan het einde van de collectie. Gekoppelde lay-outslides worden ook gekopieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide om te klonen. |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Toegevoegde slide.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Voegt een kopie van een opgegeven masterslide in op een opgegeven positie in de collectie. Gekoppelde lay-outslides worden ook gekopieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe slide. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide om te klonen. |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Ingevoegde masterslide.