---
title: VbaReferenceFactory
second_title: Aspose.Slides für Android über Java API Referenz
description: Ermöglicht das Erstellen von VBA-Projektverweisen über die COM-Schnittstelle
type: docs
url: /de/com.aspose.slides/vbareferencefactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Ermöglicht das Erstellen von VBA-Projektverweisen über die COM-Schnittstelle
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInstance()](#getInstance--) | Statische Instanz der VBA-Projektverweisfabrik. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Erstellt eine neue OLE Automation-Typbibliotheksreferenz. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Statische Instanz der VBA-Projektverweisfabrik. Nur lesbar [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Rückgabewert:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Erstellt eine neue OLE Automation-Typbibliotheksreferenz.

**Parameter:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Rückgabewert:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Neue OLE Automation-Typbibliotheksreferenz