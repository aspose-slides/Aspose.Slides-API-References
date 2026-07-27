---
title: ResolveUri()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, resuelve el URI absoluto a partir del URI base y los URI relativos.
type: docs
weight: 27
url: /es/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) método

Cuando se sobrescribe en una clase derivada, resuelve el URI absoluto a partir del URI base y los URI relativos.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI base utilizado para resolver el URI relativo. |
| relativeUri | [String](../../../system/string/) | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con el **baseUri** para crear un URI absoluto. |

### Valor devuelto

El URI absoluto o **nullptr** si el URI relativo no se puede resolver.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [XmlResolver](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)