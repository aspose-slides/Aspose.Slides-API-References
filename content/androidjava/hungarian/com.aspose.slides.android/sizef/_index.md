---
title: SizeF
second_title: Aspose.Slides for Android Java API-referencia
description: Osztály a szélesség és magasság dimenziók leírására egy tetszőleges egységben lebegőpontos értékekkel.
type: docs
url: /hu/com.aspose.slides.android/sizef/
---
**Inheritance:**
java.lang.Object
```
public class SizeF
```

Osztály a szélesség és magasság dimenziók leírására egy tetszőleges egységben lebegőpontos értékekkel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Új SizeF példány létrehozása. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getWidth()](#getWidth--) | A méret szélességének lekérése. |
| [getHeight()](#getHeight--) | A méret magasságának lekérése. |
| [equals(Object obj)](#equals-java.lang.Object-) | Ellenőrzi, hogy ez a méret egyenlő-e egy másik mérettel. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Visszaadja a méretet stringként a "WxH" formátummal |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

Új SizeF példány létrehozása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | A méret szélessége |
| height | float | A méret magassága |
### getWidth() {#getWidth--}
```
public float getWidth()
```

A méret szélességének lekérése.

**Visszatér:**
float - szélesség
### getHeight() {#getHeight--}
```
public float getHeight()
```

A méret magasságának lekérése.

**Visszatér:**
float - magasság
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Ellenőrzi, hogy ez a méret egyenlő-e egy másik mérettel.

Két méret csak akkor egyenlő, ha mind a szélességük, mind a magasságuk megegyezik.

Ehhez a szélesség/magasság lebegőpontos értékeket akkor tekintjük azonosnak, ha a Float\#floatToIntBits(float).floatToIntBits(float) metódus azonos int értéket ad vissza mindkét esetben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object |  |
**Visszatér:**
boolean - true ha az objektumok egyenlőek, false egyébként
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Visszatér:**
int
### toString() {#toString--}
```
public String toString()
```

Visszaadja a méretet stringként a "WxH" formátummal.

**Visszatér:**
java.lang.String - a méret string reprezentációja