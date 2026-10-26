---
title: Size
second_title: Aspose.Slides Androidra vonatkozó Java API referenciája
description: Osztály, amely a szélesség és magasság dimenzióit írja le egy tetszőleges egységben.
type: docs
url: /hu/com.aspose.slides.android/size/
---
**Öröklés:**
java.lang.Object
```
public class Size
```

Osztály, amely a szélesség és magasság dimenzióit írja le egy tetszőleges egységben.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Új Size példányt hoz létre. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getWidth()](#getWidth--) | A méret szélességét adja vissza. |
| [getHeight()](#getHeight--) | A méret magasságát adja vissza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Ellenőrzi, hogy ez a méret egyenlő-e egy másik mérettel. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Visszaadja a méretet egy "WxH" formátumú karakterláncként. |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Új Size példányt hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | int | A méret szélessége |
| height | int | A méret magassága |

### getWidth() {#getWidth--}
```
public int getWidth()
```

A méret szélességét adja vissza.

**Visszatérési érték:**
int - szélesség
### getHeight() {#getHeight--}
```
public int getHeight()
```

A méret magasságát adja vissza.

**Visszatérési érték:**
int - magasság
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Ellenőrzi, hogy ez a méret egyenlő-e egy másik mérettel.

Két méret akkor és csak akkor egyenlő, ha mindkettő szélessége és magassága megegyezik.

Egy Size objektum soha nem egyenlő semmilyen más típusú objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Visszatérési érték:**
boolean -  true  ha az objektumok egyenlőek voltak,  false  egyébként
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Visszatérési érték:**
int
### toString() {#toString--}
```
public String toString()
```

Visszaadja a méretet egy "WxH" formátumú karakterláncként.

**Visszatérési érték:**
java.lang.String - a méret karakterlánc ábrázolása