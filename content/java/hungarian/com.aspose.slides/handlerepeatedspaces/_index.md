---
title: HandleRepeatedSpaces
second_title: Aspose.Slides Java API hivatkozása
description: Megadja, hogyan kell kezelni az ismétlődő reguláris szóköz karaktereket Markdown exportálás során.
type: docs
url: /hu/com.aspose.slides/handlerepeatedspaces/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Megadja, hogyan kell kezelni az ismétlődő reguláris szóköz karaktereket Markdown exportáláskor.
## Mezők

| Mező | Leírás |
| --- | --- |
| [None](#None) | Minden szóköz változtatás nélkül reguláris szóköz karakterként marad meg. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Átalakítja a két vagy több egymást követő reguláris szóköz sorozatát úgy, hogy felváltva használ reguláris szóköz karaktereket és nem törő szóköz entitásokat NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Átalakítja a két vagy több egymást követő reguláris szóköz sorozatát úgy, hogy az első szóközt reguláris szóköz karakterként megőrzi, a további szóközöket pedig nem törő szóköz entitásokkal NBSP helyettesíti. |
### None {#None}
```
public static final int None
```


Minden szóköz változtatás nélkül reguláris szóköz karakterként marad meg. Nincs alkalmazott átalakítás, és a több egymást követő szóköz változtatás nélkül exportálódik.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Átalakítja a két vagy több egymást követő reguláris szóköz sorozatát úgy, hogy felváltva használ reguláris szóköz karaktereket és nem törő szóköz entitásokat NBSP. Az első szóköz mindig reguláris szóköz marad.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Átalakítja a két vagy több egymást követő reguláris szóköz sorozatát úgy, hogy az első szóközt reguláris szóköz karakterként megőrzi, a további szóközöket pedig nem törő szóköz entitásokkal NBSP helyettesíti.