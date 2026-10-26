---
title: ResolveUri()
second_title: Referencia de la API de Aspose.Slides para C++
description: Resuelve el URI absoluto a partir del URI base y los URI relativos.
type: docs
weight: 40
url: /es/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) método


Resuelve el URI absoluto a partir del URI base y los URI relativos.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI base utilizado para resolver el URI relativo. |
| relativeUri | [String](../../../system/string/) | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con el **baseUri** para crear un URI absoluto. |

### Valor devuelto

El [Uri](../../../system/uri/) que representa el URI absoluto o **nullptr** si el URI relativo no puede resolverse.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [XmlPreloadedResolver](../)
* Espacio de nombres [System::Xml::Resolvers](../../)
* Biblioteca [Aspose.Slides](../../../)