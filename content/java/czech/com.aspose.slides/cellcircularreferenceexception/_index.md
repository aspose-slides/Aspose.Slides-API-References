---
title: CellCircularReferenceException
second_title: Aspose.Slides pro Java API Reference
description: Výjimka, která je vyvolána, když jsou detekovány jedny nebo více kruhových odkazů, kde vzorec odkazuje na vlastní buňku buď přímo, nebo nepřímo.
type: docs
url: /cs/com.aspose.slides/cellcircularreferenceexception/
---
**Dědičnost:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Výjimka, která je vyvolána, když jsou detekovány jedny nebo více kruhových odkazů, kde vzorec odkazuje na vlastní buňku buď přímo, nebo nepřímo.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určeným chybovým hlášením. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určeným chybovým hlášením a odkazem na vnitřní výjimku, která je příčinou této výjimky. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určeným chybovým hlášením a kruhovým odkazem na buňku. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getReference()](#getReference--) | Získá kruhový odkaz na buňku. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určeným chybovým hlášením.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určeným chybovým hlášením a odkazem na vnitřní výjimku, která je příčinou této výjimky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |
| innerException | java.lang.RuntimeException | Výjimka, která je příčinou současné výjimky. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určeným chybovým hlášením a kruhovým odkazem na buňku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |
| reference | java.lang.String | Kruhový odkaz na buňku. |

### getReference() {#getReference--}
```
public final String getReference()
```

Získá kruhový odkaz na buňku.

**Vrací:**
java.lang.String