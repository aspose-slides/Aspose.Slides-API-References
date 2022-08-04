---
title: VbaReferenceFactory
second_title: Aspose.Sildes for Java API Reference
description: p
 Allows to create VBA project references via COM interface
type: docs
weight: 600
url: /java/com.aspose.slides/vbareferencefactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Allows to create VBA project references via COM interface
## Constructors

| Constructor | Description |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Methods

| Method | Description |
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


VBA project references factory static instance. Read-only [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Returns:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Creates new OLE Automation type library reference.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Returns:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - New OLE Automation type library reference
