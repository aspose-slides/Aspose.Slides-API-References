---
title: ISvgShape
second_title: Aspose.Slides for Java API Reference
description: Az SVG alakzat opcióit képviseli.
type: docs
url: /hu/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Az SVG alakzat opcióit képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Beállítja az alakzat eseménykezelőjét |
| [getId()](#getId--) | Beállítja vagy lekéri az alakzat azonosítóját |
| [setId(String value)](#setId-java.lang.String-) | Beállítja vagy lekéri az alakzat azonosítóját |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

Beállítja az alakzat eseménykezelőjét

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| eventType | int | Az esemény típusa. |
| handler | java.lang.String | Javascript függvény az esemény kezeléséhez. Null érték eltávolítja a kezelőt. |

### getId() {#getId--}
```
public abstract String getId()
```

Beállítja vagy lekéri az alakzat azonosítóját

**Visszatérési érték:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Beállítja vagy lekéri az alakzat azonosítóját

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |