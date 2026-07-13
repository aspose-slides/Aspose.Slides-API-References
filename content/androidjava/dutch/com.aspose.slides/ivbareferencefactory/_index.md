---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Referentie
description: Stelt u in staat VBA-projectreferenties te maken via COM-interface
type: docs
url: /nl/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Staat toe om VBA-projectreferenties te maken via COM-interface
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Creates new OLE Automation type library reference. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Maakt een nieuwe OLE Automation typebibliotheekreferentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de VBA-projectreferentie String |
| libid | java.lang.String | Identifier van een Automation typebibliotheek String |

**Retourwaarde:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nieuwe OLE Automation typebibliotheekreferentie [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)