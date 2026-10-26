---
title: VbaReferenceFactory
second_title: Aspose.Slides para Android vía referencia de API Java
description: Permite crear referencias de proyecto VBA a través de la interfaz COM
type: docs
url: /es/com.aspose.slides/vbareferencefactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Permite crear referencias de proyecto VBA a través de la interfaz COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInstance()](#getInstance--) | Instancia estática de la fábrica de referencias de proyecto VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Crea una nueva referencia a una biblioteca de tipos OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Instancia estática de la fábrica de referencias de proyecto VBA. Solo lectura [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Devuelve:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Crea una nueva referencia a una biblioteca de tipos OLE Automation.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Devuelve:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nueva referencia a una biblioteca de tipos OLE Automation