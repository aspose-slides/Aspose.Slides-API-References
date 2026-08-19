---
title: MasterSlideCollection
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een collectie van master slides.
type: docs
url: /nl/com.aspose.slides/masterslidecollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Representeert een collectie van master slides.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Verwijdert ongebruikte master slides. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Voegt een kopie van een opgegeven master slide toe aan het einde van de collectie. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Voegt een kopie van een opgegeven master slide in op een opgegeven positie in de collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd is (thread-veilig). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatieroot. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [MasterSlide](../../com.aspose.slides/masterslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Verwijdert de eerste voorkoming van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | De master slide die uit de collectie moet worden verwijderd. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element.

--------------------

Om het werpen van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van de master. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Verwijdert ongebruikte master slides.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ignorePreserveField | boolean | Bepaalt of deze methode ongebruikte master moet verwijderen zelfs als de [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-)-eigenschap op true staat. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Voegt een kopie van een opgegeven master slide toe aan het einde van de collectie. Gerelateerde layout-dia's worden ook gekopieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Dia om te klonen. |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Toegevoegde dia.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Voegt een kopie van een opgegeven master slide in op een opgegeven positie in de collectie. Gerelateerde layout-dia's worden ook gekopieerd.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instantieer Presentation-klasse om het bronpresentatiebestand te laden
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instantieer Presentation-klasse voor de bestemmingspresentatie (waar de dia naartoe gekloond moet worden)
>      Presentation destPres = new Presentation();
>      try {
>          // Instantieer ISlide uit de verzameling dia's in de bronpresentatie samen met
>          // Masterdia
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Haal masterdia's op van de bestemmingspresentatie
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Kloon de gewenste masterdia van de bronpresentatie naar de verzameling masters in de
>          // Bestemmingspresentatie
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Verzameling dia's in de bestemmingspresentatie
>          ISlideCollection slds = destPres.getSlides();
>          // Kloon brondia naar de bestemmingsdia-collectie.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Sla de bestemmingspresentatie op naar schijf
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Dia om te klonen. |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Ingevoegde master slide.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Startindex in de doel-array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd is (thread-veilig). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Retourneert een java-iterator voor de gehele collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Een java.util.Iterator voor de gehele collectie.