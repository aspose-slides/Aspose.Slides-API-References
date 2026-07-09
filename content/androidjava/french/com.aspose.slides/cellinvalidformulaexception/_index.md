---
title: CellInvalidFormulaException
second_title: Référence de l'API Java Aspose.Slides pour Android
description: L'exception qui est levée lorsqu'une formule calculée n'est pas correcte ou n'a pas été analysée.
type: docs
url: /fr/com.aspose.slides/cellinvalidformulaexception/
---
**Héritage:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

L'exception qui est levée lorsqu'une formule calculée n'est pas correcte ou n'a pas été analysée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) avec un message d'erreur spécifié. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) avec un message d'erreur spécifié et une référence à l'exception interne qui est la cause de cette exception. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) avec un message d'erreur spécifié et une référence de cellule contenant la formule non valide. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getReference()](#getReference--) | Obtient une référence de cellule contenant la formule non valide. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).
### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) avec un message d'erreur spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |
### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) avec un message d'erreur spécifié et une référence à l'exception interne qui est la cause de cette exception.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |
| innerException | java.lang.RuntimeException | L'exception qui est la cause de l'exception actuelle. |
### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Initialise une nouvelle instance de la classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) avec un message d'erreur spécifié et une référence de cellule contenant la formule non valide.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Une chaîne qui décrit l'erreur. |
| reference | java.lang.String | Une chaîne qui décrit une référence à l'exception interne |
### getReference() {#getReference--}
```
public final String getReference()
```

Obtient une référence de cellule contenant la formule non valide.

**Retour:**
java.lang.String