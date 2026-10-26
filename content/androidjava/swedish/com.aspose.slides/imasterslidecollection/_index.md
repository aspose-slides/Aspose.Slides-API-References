---
title: IMasterSlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av masterbilder.
type: docs
url: /sv/com.aspose.slides/imasterslidecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Representerar en samling av masterbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Tar bort oanvända masterbilder. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Lägger till en kopia av en specificerad masterbild i slutet av samlingen. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Infogar en kopia av en specificerad masterbild på en angiven position i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbilden som ska tas bort från samlingen. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Tar bort oanvända masterbilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ignorePreserveField | boolean | Bestämmer om den här metoden ska ta bort oanvänd master även om dess [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) egenskap är satt till true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Lägger till en kopia av en specificerad masterbild i slutet av samlingen. Länkade layoutbilder kommer också att kopieras.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Bild att klona. |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Tillagd bild.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Infogar en kopia av en specificerad masterbild på en angiven position i samlingen. Länkade layoutbilder kommer också att kopieras.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ny bild. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Bild att klona. |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Infogad masterbild.