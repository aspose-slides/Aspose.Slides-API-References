---
title: CellCircularReferenceException
second_title: Référence de l'API Java Aspose.Slides pour Android
description: L'exception qui est levée lorsqu'une ou plusieurs références circulaires sont détectées, où une formule fait référence à sa propre cellule, directement ou indirectement.
type: docs
url: /fr/com.aspose.slides/cellcircularreferenceexception/
---
**Héritage:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)  
```
public class CellCircularReferenceException extends PptxEditException
```

L'exception qui est levée lorsqu'une ou plusieurs références circulaires sont détectées, où une formule fait référence à sa propre cellule, directement ou indirectement.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié et une référence à l'exception interne qui est à l'origine de cette exception. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié et une référence de cellule circulaire. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getReference()](#getReference--) | Obtient une référence de cellule circulaire. |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié et une référence à l'exception interne qui est à l'origine de cette exception.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |
| innerException | java.lang.RuntimeException | L'exception qui est à l'origine de l'exception actuelle. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié et une référence de cellule circulaire.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |
| reference | java.lang.String | Une référence de cellule circulaire. |

### getReference() {#getReference--}
```
public final String getReference()
```

Obtient une référence de cellule circulaire.

**Renvoie:**
java.lang.String