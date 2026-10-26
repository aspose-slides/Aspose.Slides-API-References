---
title: MasterSlideCollection
second_title: Aspose.Slides Java API referencia
description: Mesterdiák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/masterslidecollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Egy mesterdia gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Lekéri a gyűjteményben valójában tárolt elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Eltávolítja a fel nem használt mesterdiákat. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | A megadott mesterdia másolatát a gyűjtemény végéhez adja hozzá. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | A megadott mesterdia másolatát a gyűjtemény megadott pozíciójába szúrja be. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Másolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Lekéri a gyűjteményben valójában tárolt elemek számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Lekéri a megadott indexű elemet. Csak olvasható [MasterSlide](../../com.aspose.slides/masterslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Eltávolítja a megadott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | A gyűjteményből eltávolítandó mesterdia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulla alapú indexe.

--------------------

A PptxEditException dobásának elkerülése érdekében ellenőrizze a master's HasDependingSlides property-t előtte. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Eltávolítja a fel nem használt mesterdiákat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ignorePreserveField | boolean | Meghatározza, hogy ez a metódus eltávolítja-e a fel nem használt mestert akkor is, ha a [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) tulajdonság true-ra van állítva. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

A megadott mesterdia másolatát a gyűjtemény végéhez adja hozzá. A kapcsolt elrendezési diák is másolásra kerülnek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klónozandó dia. |

**Visszatér:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Hozzáadott dia.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

A megadott mesterdia másolatát a gyűjtemény megadott pozíciójába szúrja be. A kapcsolt elrendezési diák is másolásra kerülnek.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt a forrás prezentációs fájl betöltéséhez
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Példányosítja a Presentation osztályt a célprezentációhoz (ahová a dia klónozva lesz)
>      Presentation destPres = new Presentation();
>      try {
>          // Példányosítja az ISlide-t a forrás prezentáció diák gyűjteményéből együtt
>          // Mesterdia
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Lekéri a célprezentáció mesterdiáit
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Klónozza a kívánt mesterdiát a forrás prezentációból a mestergyűjteménybe a
>          // Célprezentációban
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // A célprezentáció diáinak gyűjteménye
>          ISlideCollection slds = destPres.getSlides();
>          // Klónozza a forrás diát a cél diagyűjteménybe.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Mentse a célprezentációt a lemezre
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klónozandó dia. |

**Visszatér:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Beszúrt mesterdia.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Másolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - A IGenericEnumerator amely a gyűjtemény végigiterálásához használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - An java.util.Iterator for the entire collection.