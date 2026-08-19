---
title: VbaReferenceFactory
second_title: Riferimento API di Aspose.Slides per Java
description: Consente di creare riferimenti a progetti VBA tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/vbareferencefactory/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Consente di creare riferimenti a progetti VBA tramite interfaccia COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metodi

| Metodo | Descrizione |
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

Istanza statica della fabbrica di riferimenti a progetti VBA. Solo lettura [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Restituisce:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Crea un nuovo riferimento a libreria di tipo OLE Automation.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Restituisce:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nuovo riferimento a libreria di tipo OLE Automation