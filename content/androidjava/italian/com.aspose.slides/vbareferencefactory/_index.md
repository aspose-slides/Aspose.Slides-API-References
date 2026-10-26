---
title: VbaReferenceFactory
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Consente di creare riferimenti a progetti VBA tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/vbareferencefactory/
---
**Ereditarietà:**
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
| [getInstance()](#getInstance--) | Istanza statica del factory di riferimenti ai progetti VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Crea un nuovo riferimento a una libreria di tipi OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Istanza statica del factory di riferimenti ai progetti VBA. Sola lettura [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Restituisce:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Crea un nuovo riferimento a una libreria di tipi OLE Automation.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Restituisce:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nuovo riferimento a una libreria di tipi OLE Automation