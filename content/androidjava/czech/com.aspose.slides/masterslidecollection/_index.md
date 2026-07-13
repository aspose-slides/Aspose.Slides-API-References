---
title: MasterSlideCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Representuje kolekci hlavních snímků.
type: docs
url: /cs/com.aspose.slides/masterslidecollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Representuje kolekci hlavních snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Získá počet prvků skutečně obsažených v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Odstraní nepoužité hlavní snímky. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Přidá kopii zadaného hlavního snímku na konec kolekce. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Vloží kopii zadaného hlavního snímku na určenou pozici v kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrátí hodnotu označující, zda je přístup ke kolekci synchronizovaný (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrátí kořen synchronizace. |
| [iterator()](#iterator--) | Vrátí enumerátor, který iteruje přes kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```


Získá počet skutečně obsažených prvků v kolekci. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Získá prvek na zadaném indexu. Pouze pro čtení [MasterSlide](../../com.aspose.slides/masterslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Odstraní první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek, který má být z kolekce odstraněn. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index prvku, který má být odstraněn.

--------------------

Aby nedošlo k vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides hlavního snímku. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Odstraní nepoužité hlavní snímky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| ignorePreserveField | boolean | Určuje, zda má tato metoda odstranit nepoužité hlavní snímky i v případě, že je jejich vlastnost [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) nastavena na true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Přidá kopii zadaného hlavního snímku na konec kolekce. Propojené snímky rozložení budou také zkopírovány.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Snímek ke klonování. |

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Přidaný snímek.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Vloží kopii zadaného hlavního snímku na určenou pozici v kolekci. Propojené snímky rozložení budou také zkopírovány.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Vytvořte instanci třídy Presentation pro načtení souboru zdrojové prezentace
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Vytvořte instanci třídy Presentation pro cílovou prezentaci (kam bude snímek klonován)
>      Presentation destPres = new Presentation();
>      try {
>          // Vytvořte instanci ISlide ze sbírky snímků ve zdrojové prezentaci spolu s
>          // hlavním snímkem
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Získejte hlavní snímky cílové prezentace
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Klonujte požadovaný hlavní snímek ze zdrojové prezentace do sbírky hlavních snímků v
>          // cílové prezentaci
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Sbírka snímků v cílové prezentaci
>          ISlideCollection slds = destPres.getSlides();
>          // Klonujte zdrojový snímek do sbírky snímků v cíli.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Uložte cílovou prezentaci na disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Snímek ke klonování. |

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Vložený hlavní snímek.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrátí hodnotu označující, zda je přístup ke kolekci synchronizovaný (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrátí kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Vrátí enumerátor, který iteruje přes kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator pro celou kolekci.