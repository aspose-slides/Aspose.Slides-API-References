---
title: CellInvalidReferenceException
second_title: Aspose.Slides pro Android prostřednictvím Java API referenční příručka
description: Výjimka, která je vyvolána, když je zaznamenán neplatný odkaz na buňku.
type: docs
url: /cs/com.aspose.slides/cellinvalidreferenceexception/
---
**Dědičnost:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Výjimka, která je vyvolána, když je zaznamenán neplatný odkaz na buňku.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) s určenou chybovou zprávou. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) s určenou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou a neplatným odkazem na buňku. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getReference()](#getReference--) | Získá neplatný odkaz na buňku. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) s určenou chybovou zprávou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Inicializuje novou instanci třídy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) s určenou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |
| innerException | java.lang.RuntimeException | Výjimka, která je příčinou aktuální výjimky. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou a neplatným odkazem na buňku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |
| reference | java.lang.String | Neplatný odkaz na buňku. |

### getReference() {#getReference--}
```
public final String getReference()
```

Získá neplatný odkaz na buňku.

**Návratová hodnota:**
java.lang.String