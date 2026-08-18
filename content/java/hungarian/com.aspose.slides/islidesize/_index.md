---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /hu/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

A dia méretét és tájolását reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSize()](#getSize--) | A dia méreteit pontban adja vissza. |
| [getType()](#getType--) | A dia méretétípust adja vissza. |
| [getOrientation()](#getOrientation--) | A dia tájolását adja vissza vagy állítja be. |
| [setOrientation(int value)](#setOrientation-int-) | A dia tájolását adja vissza vagy állítja be. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Beállítja a dia méretét típus alapján, és skálázza a meglévő tartalmat. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | A dia méretét explicit módon állítja be, és skálázza a meglévő tartalmat. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


A dia méreteit pontban adja vissza.

--------------------

Új érték hozzárendelése visszaállítja a \#getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket.

**Visszatérési érték:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


A dia méretétípust adja vissza.

--------------------

Bármely, a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)-tól eltérő érték hozzárendelése a \#getSize.getSize-ot a meghatározott méretek szerint módosítja, miközben megtartja az aktuális \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) beállítást.

**Visszatérési érték:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


A dia tájolását adja vissza vagy állítja be.

--------------------

Az érték megváltoztatása felcseréli a dia szélességét és magasságát.

**Visszatérési érték:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


A dia tájolását adja vissza vagy állítja be.

--------------------

Az érték megváltoztatása felcseréli a dia szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Beállítja a dia méretét típus alapján, és skálázza a meglévő tartalmat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A alkalmazandó előre definiált dia méret. |
| scaleType | int | A használandó tartalom skálázási mód. |

--------------------

Bármely, a [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)-tól eltérő érték hozzárendelése a \#getSize.getSize-ot a kiválasztott típus alapján módosítja, miközben megőrzi a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) beállítást. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


A dia méretét explicit módon állítja be, és skálázza a meglévő tartalmat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | Az új dia szélessége pontban. |
| height | float | Az új dia magassága pontban. |
| scaleType | int | A használandó tartalom skálázási mód. |

--------------------

Ez visszaállítja a \#getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket. |