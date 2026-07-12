---
title: IMasterSlideCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Mesterdiák gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/imasterslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Egy mesterdia gyűjteményét reprezentálja.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexen lévő elemet. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexen lévő elemet a gyűjteményből. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Eltávolítja a nem használt mesterdiákat. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Hozzáad egy megadott mesterdia másolatát a gyűjtemény végéhez. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Beszúr egy megadott mesterdia másolatát a gyűjtemény megadott pozíciójába. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


Lekéri a megadott indexen lévő elemet. Csak olvasható [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


Eltávolítja a megadott objektum első előfordulását a gyűjteményből.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | A gyűjteményből eltávolítandó mesterdia. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a megadott indexen lévő elemet a gyűjteményből.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A nullától kezdődő indexe az eltávolítandó elemnek. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


Eltávolítja a nem használt mesterdiákat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | Meghatározza, hogy a metódus eltávolítsa-e a nem használt mestert akkor is, ha annak [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) tulajdonsága true értékre van állítva. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


Hozzáad egy megadott mesterdia másolatát a gyűjtemény végéhez. A kapcsolt elrendezési diák is másolva lesznek.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klónozandó dia. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Hozzáadott dia.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Beszúr egy megadott mesterdia másolatát a gyűjtemény megadott pozíciójába. A kapcsolt elrendezési diák is másolva lesznek.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klónozandó dia. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Beszúrt mesterdia.