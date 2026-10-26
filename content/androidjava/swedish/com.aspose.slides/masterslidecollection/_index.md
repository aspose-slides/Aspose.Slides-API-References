---
title: MasterSlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av masterbilder.
type: docs
url: /sv/com.aspose.slides/masterslidecollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Representerar en samling av masterbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Tar bort oanvända masterbilder. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Lägger till en kopia av en specificerad masterbild i slutet av samlingen. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Infogar en kopia av en specificerad masterbild på en specificerad position i samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### size() {#size--}
```
public final int size()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [MasterSlide](../../com.aspose.slides/masterslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbilden som ska tas bort från samlingen. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort.

--------------------

För att undvika att PptxEditException kastas, kontrollera masterns HasDependingSlides-egenskap innan. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Tar bort oanvända masterbilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ignorePreserveField | boolean | Bestämmer om denna metod ska ta bort oanvänd master även om dess [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) egenskap är satt till true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
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
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Infogar en kopia av en specificerad masterbild på en specificerad position i samlingen. Länkade layoutbilder kommer också att kopieras.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instantiate Presentation class for destination presentation (where slide is to be cloned)
>      Presentation destPres = new Presentation();
>      try {
>          // Instantiate ISlide from the collection of slides in source presentation along with
>          // Master slide
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Get Master Slides of destination presentation
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clone the desired master slide from the source presentation to the collection of masters in the
>          // Destination presentation
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Collection of slides in the destination presentation
>          ISlideCollection slds = destPres.getSlides();
>          // Clone source slide to destination slides collection.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Save the destination presentation to disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ny bild. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Bild att klona. |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Infogad masterbild.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarrayen.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (thread-safe). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - En java.util.Iterator för hela samlingen.