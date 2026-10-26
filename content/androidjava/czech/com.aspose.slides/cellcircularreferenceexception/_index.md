---
title: CellCircularReferenceException
second_title: Aspose.Slides pro Android pomocí referenční dokumentace Java API
description: Výjimka, která je vyvolána, když je detekována jedna nebo více kruhových referencí, kde vzorec odkazuje na svou vlastní buňku buď přímo, nebo nepřímo.
type: docs
url: /cs/com.aspose.slides/cellcircularreferenceexception/
---
**Dědičnost:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Výjimka, která je vyvolána, když jsou detekovány jedna nebo více kruhových referencí, kde vzorec odkazuje na svou vlastní buňku buď přímo, nebo nepřímo.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou a kruhovou referencí buňky. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getReference()](#getReference--) | Získá kruhovou referenci buňky. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec popisující chybu. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec popisující chybu. |
| innerException | java.lang.RuntimeException | Výjimka, která je příčinou aktuální výjimky. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Inicializuje novou instanci třídy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) s určenou chybovou zprávou a kruhovou referencí buňky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec popisující chybu. |
| reference | java.lang.String | Kruhová reference buňky. |

### getReference() {#getReference--}
```
public final String getReference()
```

Získá kruhovou referenci buňky.

**Návratová hodnota:**
java.lang.String