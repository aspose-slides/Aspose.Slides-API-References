---
title: VbaReferenceFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe om VBA-projectreferenties via COM-interface te maken
type: docs
url: /nl/com.aspose.slides/vbareferencefactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Sta toe om VBA-projectreferenties via COM-interface te maken

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project references factory static instance. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Creates new OLE Automation type library reference. |

### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```

### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

VBA project references factory static instance. Alleen-lezen [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Retourwaarde:**
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

**Retourwaarde:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nieuwe OLE Automation typebibliotheekreferentie