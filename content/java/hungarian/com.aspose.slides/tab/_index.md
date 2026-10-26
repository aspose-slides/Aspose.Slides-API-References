---
title: Tab
second_title: Aspose.Slides for Java API referencia
description: Szöveghez tartozó tabulációt képvisel.
type: docs
url: /hu/com.aspose.slides/tab/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Szöveghez tartozó tabulációt képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Creates new Tab |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Returns or sets position of a tab. |
| [setPosition(double value)](#setPosition-double-) | Returns or sets position of a tab. |
| [getAlignment()](#getAlignment--) | Returns or sets align style of a tab. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets align style of a tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the current instance with another object of the same type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Új Tab létrehozása

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | double | Tab position. |
| align | int | Align. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

A tab pozícióját adja vissza vagy állítja be. Ennek a tulajdonságnak az értékadása megváltoztathatja a tab indexét a gyűjteményben, és érvénytelenítheti az Enumerator-t. Olvasás/írás double.

**Visszatér:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

A tab pozícióját adja vissza vagy állítja be. Ennek a tulajdonságnak az értékadása megváltoztathatja a tab indexét a gyűjteményben, és érvénytelenítheti az Enumerator-t. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

A tab igazítási stílusát adja vissza vagy állítja be. Olvasás/írás [TabAlignment](../../com.aspose.slides/tabalignment).

**Visszatér:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

A tab igazítási stílusát adja vissza vagy állítja be. Olvasás/írás [TabAlignment](../../com.aspose.slides/tabalignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Összehasonlítja a jelenlegi példányt egy ugyanazon típusú másik objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Egy objektum, amely összehasonlítandó ezzel a példánnyal. |

**Visszatér:**
int - Egy 32 bites egész szám, amely a hasonlított elemek relatív sorrendjét jelzi. A visszatérési érték a következő jelentésekkel bír:

 * < 0 - Ez az példány kisebb, mint az obj.
 * = 0 - Ez az példány egyenlő az obj-val.
 * > 0 - Ez az példány nagyobb, mint az obj.