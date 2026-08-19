---
title: CellInvalidReferenceException
second_title: Aspose.Slides pro Java - reference API
description: Výjimka, která se vyvolá, když je nalezena neplatná reference buňky.
type: docs
url: /cs/com.aspose.slides/cellinvalidreferenceexception/
---
**Dědičnost:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Výjimka, která je vyvolána při nalezení neplatné reference buňky.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) se zadanou chybovou zprávou. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) se zadanou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) se zadanou chybovou zprávou a neplatnou referencí buňky. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getReference()](#getReference--) | Získá neplatnou referenci buňky. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) se zadanou chybovou zprávou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec popisující chybu. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) se zadanou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec popisující chybu. |
| innerException | java.lang.RuntimeException | Výjimka, která je příčinou aktuální výjimky. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) se zadanou chybovou zprávou a neplatnou referencí buňky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec popisující chybu. |
| reference | java.lang.String | Neplatná reference buňky. |

### getReference() {#getReference--}
```
public final String getReference()
```

Získá neplatnou referenci buňky.

**Vrací:**
java.lang.String