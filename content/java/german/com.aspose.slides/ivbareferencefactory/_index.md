---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Java API Reference
description: Ermöglicht das Erstellen von VBA-Projektverweisen über die COM-Schnittstelle
type: docs
url: /de/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Ermöglicht das Erstellen von VBA-Projektverweisen über die COM-Schnittstelle
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE-Automatisierungstypbibliotheksverweis. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Erstellt einen neuen OLE-Automatisierungstypbibliotheksverweis.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des VBA-Projektverweises String |
| libid | java.lang.String | Bezeichner einer Automation-Typbibliothek String |

**Rückgabewert:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Neuer OLE-Automatisierungstypbibliotheksverweis [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)