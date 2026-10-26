---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta le opzioni per la forma SVG.
type: docs
url: /it/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Rappresenta le opzioni per la forma SVG.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Sets event handler for the shape |
| [getId()](#getId--) | Sets or gets id for the shape |
| [setId(String value)](#setId-java.lang.String-) | Sets or gets id for the shape |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

Imposta il gestore dell'evento per la forma

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | int | Tipo di evento. |
| handler | java.lang.String | Funzione JavaScript per gestire l'evento. Un valore null rimuove il gestore. |

### getId() {#getId--}
```
public abstract String getId()
```

Imposta o ottiene l'id per la forma

**Restituisce:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Imposta o ottiene l'id per la forma

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |