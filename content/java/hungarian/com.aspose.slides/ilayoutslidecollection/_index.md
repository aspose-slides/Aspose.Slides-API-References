---
title: ILayoutSlideCollection
second_title: Aspose.Slides Java API Referenciája
description: Egy elrendezés diák gyűjteményének alaposztályát képviseli.
type: docs
url: /hu/com.aspose.slides/ilayoutslidecollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Egy elrendezés diák gyűjteményének alaposztályát jelöli.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elrendezés diát index alapján. |
| [getByType(byte type)](#getByType-byte-) | Visszaadja a megadott típusú első elrendezés diát. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Eltávolít egy elrendezést a gyűjteményből. |
| [removeUnused()](#removeUnused--) | Eltávolítja a nem használt elrendezés diákat (azok a elrendezés diák, amelyeknél a HasDependingSlides hamis). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Visszaadja az elrendezés diát index alapján. Csak olvasható [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Visszaadja a megadott típusú első elrendezés diát.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | A keresendő elrendezés dia típusa. |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) a megadott típussal vagy null, ha nem található elrendezés.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Eltávolít egy elrendezést a gyűjteményből.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Az elrendezés dia, amelyet el kell távolítani a gyűjteményből.

--------------------

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze előre az elrendezés HasDependingSlides tulajdonságát. 2) A [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódust is használhatja a kód egyszerűsítéséhez. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Eltávolítja a nem használt elrendezés diákat (azok a elrendezés diák, amelyeknél a HasDependingSlides hamis).