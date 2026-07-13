---
title: IVbaReferenceFactory
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Consente di creare riferimenti a progetti VBA tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Consente di creare riferimenti a progetti VBA tramite interfaccia COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Crea un nuovo riferimento a una libreria di tipo OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Crea un nuovo riferimento a una libreria di tipo OLE Automation.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome del riferimento al progetto VBA String |
| libid | java.lang.String | Identificatore di una libreria di tipo Automation String |

**Restituisce:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nuovo riferimento a una libreria di tipo OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)