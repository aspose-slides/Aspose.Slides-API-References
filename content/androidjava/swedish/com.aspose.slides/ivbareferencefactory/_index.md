---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa VBA-projektreferenser via COM-gränssnitt
type: docs
url: /sv/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Tillåter att skapa VBA-projektreferenser via COM-gränssnitt
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Skapar en ny OLE Automation-typbiblioteksreferens. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Skapar en ny OLE Automation-typbiblioteksreferens.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på VBA-projektreferens String |
| libid | java.lang.String | Identifierare för ett Automation-typbibliotek String |

**Returnerar:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Ny OLE Automation-typbiblioteksreferens [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)