---
title: MasterSlideCollection
second_title: Aspose.Slides for Android Java API-referencia
description: A master diák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/masterslidecollection/
---
**Öröklődés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

A főbb diák gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Removes unused master slides. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified master slide to the end of the collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserts a copy of a specified master slide to specified position of the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```

A gyűjteményben ténylegesen lévő elemek számát adja vissza. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [MasterSlide](../../com.aspose.slides/masterslide).

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

Eltávolítja egy adott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | A gyűjteményből eltávolítandó master dia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a megadott indexű elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó elem nulláral kezdődő indexe.

--------------------

A PptxEditException kivétel dobásának elkerülése érdekében ellenőrizze a master **HasDependingSlides** tulajdonságát előre. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Eltávolítja a nem használt master diákot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ignorePreserveField | boolean | Meghatározza, hogy ez a metódus eltávolítsa-e a nem használt mastert, még akkor is, ha annak [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) tulajdonsága true-ra van állítva. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

A megadott master dia másolatát hozzáadja a gyűjtemény végéhez. A kapcsolt elrendezési diák is másolásra kerülnek.

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

A megadott master dia másolatát a gyűjtemény megadott pozíciójába illeszti. A kapcsolt elrendezési diák is másolásra kerülnek.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt a forrás prezentációs fájl betöltéséhez
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Példányosítja a Presentation osztályt a cél prezentációhoz (ahová a dia klónozva lesz)
>      Presentation destPres = new Presentation();
>      try {
>          // Példányosítja az ISlide-ot a forrás prezentáció diák gyűjteményéből, együtt
>          // Master dia
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Lekéri a cél prezentáció Master diáit
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Klónozza a kívánt master diát a forrás prezentációból a master gyűjteménybe a
>          // Cél prezentációban
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // A cél prezentáció diakészlete
>          ISlideCollection slds = destPres.getSlides();
>          // Klónozza a forrás diát a cél diágyűjteménybe.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Elmenti a cél prezentációt a lemezre
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
[IMasterSlide](../../com.aspose.slides/imasterslide) - Beszúrt master dia.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

A gyűjtemény összes elemét a megadott tömbbe másolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszatér egy értékkel, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszatér egy szinkronizációs gyökérrel. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Visszatér egy enumerátorral, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Visszatér egy java iteratorral a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Egy java.util.Iterator a teljes gyűjteményhez.