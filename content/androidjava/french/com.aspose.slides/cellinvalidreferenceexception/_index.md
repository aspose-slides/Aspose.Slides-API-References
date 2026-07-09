---
title: CellInvalidReferenceException
second_title: Aspose.Slides pour Android via Java API Référence
description: L'exception qui est levée lorsqu'une référence de cellule invalide est rencontrée.
type: docs
url: /fr/com.aspose.slides/cellinvalidreferenceexception/
---
**Héritage:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

L'exception qui est levée lorsqu'une référence de cellule invalide est rencontrée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Initialise une nouvelle instance de la classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Initialise une nouvelle instance de la classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) avec un message d'erreur spécifié. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Initialise une nouvelle instance de la classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) avec un message d'erreur spécifié et une référence à l'exception interne qui est à l'origine de cette exception. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié et une référence de cellule invalide. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getReference()](#getReference--) | Obtient une référence de cellule invalide. |

### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Initialise une nouvelle instance de la classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Initialise une nouvelle instance de la classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) avec un message d'erreur spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Initialise une nouvelle instance de la classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) avec un message d'erreur spécifié et une référence à l'exception interne qui est à l'origine de cette exception.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |
| innerException | java.lang.RuntimeException | L'exception qui est à l'origine de l'exception actuelle. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Initialise une nouvelle instance de la classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) avec un message d'erreur spécifié et une référence de cellule invalide.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |
| reference | java.lang.String | Une référence de cellule invalide. |

### getReference() {#getReference--}
```
public final String getReference()
```

Obtient une référence de cellule invalide.

**Renvoie :**
java.lang.String