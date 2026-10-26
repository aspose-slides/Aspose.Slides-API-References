---
title: ResolveUri()
second_title: Referencia de API de Aspose.Slides para C++
description: Resuelve el URI absoluto a partir del URI base y del URI relativo.
type: docs
weight: 66
url: /es/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) método

Resuelve el URI absoluto a partir de los URIs base y relativo.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI base usado para resolver el URI relativo. |
| relativeUri | [String](../../../system/string/) | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con el **baseUri** para formar un URI absoluto. |

### Valor de retorno

El URI absoluto, o **nullptr** si no se puede resolver el URI relativo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [XmlUrlResolver](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)