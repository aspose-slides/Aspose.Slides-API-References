---
title: IVbaReferenceFactory
second_title: Referencia de API de Aspose.Slides para Java
description: Permite crear referencias de proyecto VBA a través de la interfaz COM
type: docs
url: /es/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Permite crear referencias de proyecto VBA a través de la interfaz COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Crea una nueva referencia de biblioteca de tipos OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Crea una nueva referencia de biblioteca de tipos OLE Automation.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la referencia del proyecto VBA String |
| libid | java.lang.String | Identificador de una biblioteca de tipos Automation String |

**Devuelve:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nueva referencia de biblioteca de tipos OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)