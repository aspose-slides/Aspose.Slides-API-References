---
title: HandleRepeatedSpaces
second_title: Aspose.Slides Androidra a Java API hivatkozásban
description: Megadja, hogyan kell kezelni a többször ismétlődő normál szóköz karaktereket a Markdown exportálás során.
type: docs
url: /hu/com.aspose.slides/handlerepeatedspaces/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Meghatározza, hogyan kell kezelni a többször ismétlődő normál szóköz karaktereket a Markdown exportálás során.
## Mezők

| Mező | Leírás |
| --- | --- |
| [None](#None) | Az összes szóköz változtatás nélkül megmarad normál szóköz karakterként. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Két vagy több egymást követő normál szóköz sorozatát úgy alakítja, hogy a reguláris szóköz karakterek és a nem törődik szóköz entitás (NBSP) felváltva jelennek meg. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Két vagy több egymást követő normál szóköz sorozatát úgy alakítja, hogy az első szóköz megmarad reguláris szóköz karakterként, a további szóközöket pedig nem törődik szóköz entitásokra (NBSP) cseréli. |
### None {#None}
```
public static final int None
```


Az összes szóköz változtatás nélkül megmarad normál szóköz karakterként. Nem alkalmaznak átalakítást, és a több egymást követő szóköz változatlanul kerül exportálásra.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Két vagy több egymást követő normál szóköz sorozatát úgy alakítja, hogy a reguláris szóköz karakterek és a nem törődik szóköz entitás (NBSP) felváltva jelennek meg. Az első szóköz mindig megmarad reguláris szóközként.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Két vagy több egymást követő normál szóköz sorozatát úgy alakítja, hogy az első szóköz megmarad reguláris szóköz karakterként, a további szóközöket pedig nem törődik szóköz entitásokra (NBSP) cseréli.