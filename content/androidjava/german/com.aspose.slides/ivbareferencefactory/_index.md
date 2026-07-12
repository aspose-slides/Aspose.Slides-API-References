---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Erlaubt das Erstellen von VBA-Projektreferenzen über die COM-Schnittstelle
type: docs
url: /de/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Erlaubt das Erstellen von VBA-Projektreferenzen über die COM-Schnittstelle
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE Automation type library reference. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Erstellt einen neuen OLE Automation type library reference.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der VBA-Projektreferenz String |
| libid | java.lang.String | Bezeichner einer Automation type library String |

**Rückgabewert:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Neue OLE Automation type library reference [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)