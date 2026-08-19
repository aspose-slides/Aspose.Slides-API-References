---
title: VbaReferenceFactory
second_title: Aspose.Slides voor Java API Referentie
description: Staat toe om VBA-projectreferenties te maken via de COM-interface
type: docs
url: /nl/com.aspose.slides/vbareferencefactory/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Staat toe om VBA-projectreferenties te maken via de COM-interface
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | VBA-projectreferenties-fabriek statische instantie. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Maakt een nieuwe OLE Automation typebibliotheekreferentie. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA-projectreferenties-fabriek statische instantie. Alleen-lezen [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Retour:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Maakt een nieuwe OLE Automation typebibliotheekreferentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Retour:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nieuwe OLE Automation typebibliotheekreferentie