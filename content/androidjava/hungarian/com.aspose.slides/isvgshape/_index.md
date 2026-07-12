---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: Az SVG alakzat beállításait képviseli.
type: docs
url: /hu/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Az SVG alakzat beállításait képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Beállítja az eseménykezelőt az alakzathoz |
| [getId()](#getId--) | Beállítja vagy lekérdezi az alakzat azonosítóját |
| [setId(String value)](#setId-java.lang.String-) | Beállítja vagy lekérdezi az alakzat azonosítóját |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


Beállítja az eseménykezelőt az alakzathoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| eventType | int | Az esemény típusa. |
| handler | java.lang.String | Javascript függvény az esemény kezeléséhez. Null érték eltávolítja a kezelőt. |

### getId() {#getId--}
```
public abstract String getId()
```


Beállítja vagy lekérdezi az alakzat azonosítóját

**Visszatérési érték:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Beállítja vagy lekérdezi az alakzat azonosítóját

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |