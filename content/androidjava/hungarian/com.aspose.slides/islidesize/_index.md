---
title: ISlideSize
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Képviseli egy dia méretét és tájolását.
type: docs
url: /hu/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Képviseli egy dia méretét és tájolását.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSize()](#getSize--) | A dia méreteit pontban adja vissza. |
| [getType()](#getType--) | A dia mérettípust adja vissza. |
| [getOrientation()](#getOrientation--) | A dia tájolását adja vissza vagy állítja be. |
| [setOrientation(int value)](#setOrientation-int-) | A dia tájolását adja vissza vagy állítja be. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | A dia méretét típussal állítja be, és a meglévő tartalmat átméretezi. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | A dia méreteit kifejezetten állítja be, és a meglévő tartalmat átméretezi. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

A dia méreteit pontban adja vissza.

--------------------

Új érték hozzárendelése visszaállítja a \#getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket.

**Visszatérési érték:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

A dia mérettípust adja vissza.

--------------------

A [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)-tól eltérő érték hozzárendelése a \#getSize.getSize értékét a predefined dimenziók szerint módosítja, miközben a jelenlegi \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) beállítást megtartja.

**Visszatérési érték:**
int
### getOrientation() {#getOrientation--}
```java
public abstract int getOrientation()
```

A dia tájolását adja vissza vagy állítja be.

--------------------

Az érték módosítása felcseréli a dia szélességét és magasságát.

**Visszatérési érték:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

A dia tájolását adja vissza vagy állítja be.

--------------------

Az érték módosítása felcseréli a dia szélességét és magasságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

A dia méretét típussal állítja be, és a meglévő tartalmat átméretezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Az alkalmazandó előre definiált dia méret. |
| scaleType | int | A használandó tartalom-átméretezési mód. |

--------------------

A [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)-tól eltérő érték hozzárendelése a \#getSize.getSize értékét a kiválasztott típus szerint módosítja, miközben a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) beállítást megőrzi. |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

A dia méreteit kifejezetten állítja be, és a meglévő tartalmat átméretezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | Az új dia szélessége pontban. |
| height | float | Az új dia magassága pontban. |
| scaleType | int | A használandó tartalom-átméretezési mód. |

--------------------

Ez visszaállítja a \#getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) értéket.