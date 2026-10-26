---
title: CellInvalidFormulaException
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Výjimka, která je vyhozena, když je vypočtený vzorec nesprávný nebo nebyl parsován.
type: docs
url: /cs/com.aspose.slides/cellinvalidformulaexception/
---
**Dědičnost:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Výjimka, která je vyhozena, když je vypočtený vzorec nesprávný nebo nebyl parsován.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) s určenou chybovou zprávou. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) s určenou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) s určenou chybovou zprávou a referencí buňky, která obsahuje neplatný vzorec. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getReference()](#getReference--) | Získá referenci buňky, která obsahuje neplatný vzorec. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) s určenou chybovou zprávou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) s určenou chybovou zprávou a odkazem na vnitřní výjimku, která je příčinou této výjimky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |
| innerException | java.lang.RuntimeException | Výjimka, která je příčinou aktuální výjimky. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Inicializuje novou instanci třídy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) s určenou chybovou zprávou a referencí buňky, která obsahuje neplatný vzorec.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | Řetězec, který popisuje chybu. |
| reference | java.lang.String | Řetězec, který popisuje odkaz na vnitřní výjimku |

### getReference() {#getReference--}
```
public final String getReference()
```

Získá referenci buňky, která obsahuje neplatný vzorec.

**Vrací:**
java.lang.String