---
title: SlideSize
second_title: Aspose.Slides for Java API Referencia
description: A dia méretét és tájolását reprezentálja.
type: docs
url: /hu/com.aspose.slides/slidesize/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

A dia méretét és tájolását reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSize()](#getSize--) | Lekéri a dia méreteit pontokban. |
| [getType()](#getType--) | Lekéri a dia méret típusát. |
| [getOrientation()](#getOrientation--) | Lekéri vagy beállítja a dia tájolását. |
| [setOrientation(int value)](#setOrientation-int-) | Lekéri vagy beállítja a dia tájolását. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Beállítja a dia méretét típus alapján, és méretezi a meglévő tartalmat. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Kifejezetten beállítja a dia méreteit, és méretezi a meglévő tartalmat. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


Lekéri a dia méreteit pontokban.

--------------------

Új érték hozzárendelése visszaállítja a \#getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket.

**Visszatérési érték:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```


Lekéri a dia méret típusát.

--------------------

Bármilyen, [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)-től eltérő érték hozzárendelése a \#getSize.getSize-ot a előre definiált méretek szerint módosítja, miközben megtartja a jelenlegi \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket.

**Visszatérési érték:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Lekéri vagy beállítja a dia tájolását.

--------------------

Az érték módosítása felcseréli a dia szélességét és magasságát.

**Visszatérési érték:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Lekéri vagy beállítja a dia tájolását.

--------------------

Az érték módosítása felcseréli a dia szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Beállítja a dia méretét típus alapján, és méretezi a meglévő tartalmat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Az alkalmazandó előre definiált dia méret. |
| scaleType | int | A használandó tartalom méretezési mód. |

--------------------

Bármilyen, [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)-től eltérő érték hozzárendelése a \#getSize.getSize-ot a kiválasztott típus alapján módosítja, miközben megőrzi a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Beállítja a dia méreteit kifejezetten, és méretezi a meglévő tartalmat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | Az új dia szélessége pontokban. |
| height | float | Az új dia magassága pontokban. |
| scaleType | int | A használandó tartalom méretezési mód. |

--------------------

Ez visszaállítja a \#getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket. |