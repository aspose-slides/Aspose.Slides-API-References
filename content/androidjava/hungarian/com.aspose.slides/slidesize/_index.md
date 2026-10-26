---
title: SlideSize
second_title: Aspose.Slides for Android Java API referencia
description: A dia méretét és tájolását képviseli.
type: docs
url: /hu/com.aspose.slides/slidesize/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Képviseli a dia méretét és tájolását.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSize()](#getSize--) | Pontokban adja vissza a dia méreteit. |
| [getType()](#getType--) | A dia mérettípusát adja vissza. |
| [getOrientation()](#getOrientation--) | A dia tájolását adja vissza vagy állítja be. |
| [setOrientation(int value)](#setOrientation-int-) | A dia tájolását adja vissza vagy állítja be. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Beállítja a dia méretét típus szerint, és méretez a meglévő tartalmat. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Kifejezetten beállítja a dia méreteit, és méretez a meglévő tartalmat. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```

Pontokban adja vissza a dia méreteit.

--------------------

Új érték hozzárendelése visszaállítja a #getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) értékét.

**Visszatér:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

A dia mérettípusát adja vissza.

--------------------

Az [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) kivételével bármely érték hozzárendelése módosítja a #getSize.getSize értékét az előre definiált méreteknek megfelelően, miközben megtartja a jelenlegi #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) beállítást.

**Visszatér:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

A dia tájolását adja vissza vagy állítja be.

--------------------

Az érték módosítása felcseréli a dia szélességét és magasságát.

**Visszatér:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
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
public final void setSize(int type, int scaleType)
```

Beállítja a dia méretét típus szerint, és méretez a meglévő tartalmat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Az alkalmazandó előre definiált dia méret. |
| scaleType | int | A használandó tartalomméretezési mód. |

--------------------

A [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) kivételével bármely érték hozzárendelése módosítja a #getSize.getSize értékét a kiválasztott típus alapján, miközben megőrzi a #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) beállítást. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Kifejezetten beállítja a dia méreteit, és méretez a meglévő tartalmat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | Az új dia szélessége pontokban. |
| height | float | Az új dia magassága pontokban. |
| scaleType | int | A használandó tartalomméretezési mód. |

--------------------

Ez visszaállítja a #getType.getType tulajdonságot [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) értékre, és beállítja a #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) értékét.