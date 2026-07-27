---
title: ResolveUri()
second_title: Referencia de la API de Aspose.Slides para C++
description: Resuelve el URI absoluto a partir de los URIs base y relativos llamando a ResolveUri en el XmlResolver subyacente.
type: docs
weight: 40
url: /es/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) método

Resuelve el URI absoluto a partir de los URIs base y relativos llamando a **ResolveUri** en el [XmlResolver](../../xmlresolver/) subyacente.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI base usado para resolver el URI relativo. |
| relativeUri | [String](../../../system/string/) | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor **baseUri**. Si es relativo, se combina con el **baseUri** para crear un URI absoluto. |

### Valor devuelto

El URI absoluto o **nullptr** si no se puede resolver el URI relativo (devuelto al llamar a **ResolveUri** en el [XmlResolver](../../xmlresolver/) subyacente).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [XmlSecureResolver](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)