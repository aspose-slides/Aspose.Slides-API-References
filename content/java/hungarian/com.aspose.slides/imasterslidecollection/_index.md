---
title: IMasterSlideCollection
second_title: Aspose.Slides Java API referencia
description: A mesterdiák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imasterslidecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

A mesterdia gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexnél. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Eltávolítja a konkrét objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Eltávolítja a nem használt mesterdiakat. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | A gyűjtemény végéhez egy megadott mesterdia másolatát adja hozzá. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Beszúr egy megadott mesterdia másolatát a gyűjtemény megadott pozíciójába. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Lekéri az elemet a megadott indexnél. Csak olvasható [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Eltávolítja a konkrét objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | A gyűjteményből eltávolítandó mesterdia. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a megadott indexű elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nullától kezdődő indexe. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Eltávolítja a nem használt mesterdiakat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ignorePreserveField | boolean | Meghatározza, hogy a metódus eltávolítsa-e a nem használt mestert akkor is, ha annak [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) tulajdonsága true értékre van állítva. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

A gyűjtemény végéhez egy megadott mesterdia másolatát adja hozzá. A kapcsolt elrendezés diaok is másolásra kerülnek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | A klónozandó dia. |

**Visszatérési érték:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Hozzáadott dia.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Beszúr egy megadott mesterdia másolatát a gyűjtemény megadott pozíciójába. A kapcsolt elrendezés diaok is másolásra kerülnek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | A klónozandó dia. |

**Visszatérési érték:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Beszúrt mesterdia.