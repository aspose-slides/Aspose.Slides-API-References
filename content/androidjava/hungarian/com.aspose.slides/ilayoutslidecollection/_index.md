---
title: ILayoutSlideCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Az elrendezési diák gyűjteményéhez tartozó alap osztályt képviseli.
type: docs
url: /hu/com.aspose.slides/ilayoutslidecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Egy alap osztályt képvisel az elrendezési diák gyűjteményéhez.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elrendezési diát. |
| [getByType(byte type)](#getByType-byte-) | Visszaadja a megadott típusú első elrendezési diát. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Eltávolít egy elrendezést a gyűjteményből. |
| [removeUnused()](#removeUnused--) | Eltávolítja a nem használt elrendezési diákat (azokat a elrendezési diákat, amelyeknek a HasDependingSlides értéke false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Visszaadja a megadott indexű elrendezési diát. Csak olvasható [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Visszaadja a megadott típusú első elrendezési diát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | byte | Az elrendezési dia megtalálásához szükséges típus. |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) a megadott típussal vagy null, ha nincs elrendezés.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Eltávolít egy elrendezést a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Az elrendezési dia, amelyet el kell távolítani a gyűjteményből. |

--------------------

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte. 2) Használhatja a [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódust is a kód egyszerűsítéséhez. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Eltávolítja a nem használt elrendezési diákat (azokat a elrendezési diákat, amelyeknek a HasDependingSlides értéke false).