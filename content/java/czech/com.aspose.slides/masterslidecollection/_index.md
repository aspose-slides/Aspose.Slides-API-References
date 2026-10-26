---
title: MasterSlideCollection
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje kolekci hlavních snímků.
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

Představuje kolekci hlavních snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Získá počet skutečně obsažených prvků v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Odebere první výskyt konkrétního objektu z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odebere prvek na určeném indexu v kolekci. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Odebere nepoužité hlavní snímky. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Přidá kopii určeného hlavního snímku na konec kolekce. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Vloží kopii určeného hlavního snímku na určenou pozici v kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
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

Získá prvek na určeném indexu. Pouze pro čtení [MasterSlide](../../com.aspose.slides/masterslide).

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

Odebere první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek, který má být odebrán z kolekce. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odebere prvek na určeném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odebrán. |

--------------------

Aby se zabránilo vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides hlavního snímku. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Odebere nepoužité hlavní snímky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| ignorePreserveField | boolean | Určuje, zda by tato metoda měla odstranit nepoužité hlavní snímky, i když je jejich [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) vlastnost nastavena na true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Přidá kopii určeného hlavního snímku na konec kolekce. Propojené snímky rozvržení budou také zkopírovány.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Snímek k duplikaci. |

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Přidaný snímek.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Vloží kopii určeného hlavního snímku na určenou pozici v kolekci. Propojené snímky rozvržení budou také zkopírovány.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Vytvořte instanci třídy Presentation pro načtení zdrojového souboru prezentace
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Vytvořte instanci třídy Presentation pro cílovou prezentaci (kde bude snímek klonován)
>      Presentation destPres = new Presentation();
>      try {
>          // Vytvořte instanci ISlide z kolekce snímků ve zdrojové prezentaci spolu
>          // Hlavní snímek
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Získejte hlavní snímky cílové prezentace
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Zkopírujte požadovaný hlavní snímek ze zdrojové prezentace do kolekce hlavních snímků v
>          // cílové prezentaci
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Kolekce snímků v cílové prezentaci
>          ISlideCollection slds = destPres.getSlides();
>          // Zkopírujte zdrojový snímek do kolekce snímků cílové prezentace.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Uložte cílovou prezentaci na disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Snímek k duplikaci. |

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Vložený hlavní snímek.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - IGenericEnumerator, který lze použít pro iteraci kolekce.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Vrací java iterator pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator pro celou kolekci.