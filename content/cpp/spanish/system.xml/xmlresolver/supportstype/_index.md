---
title: SupportsType()
second_title: Referencia de API de Aspose.Slides para C++
description: Permite al resolvedor devolver tipos distintos de Stream.
type: docs
weight: 40
url: /es/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method


Permite al resolvedor devolver tipos distintos de Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | El tipo a devolver. |

### Valor devuelto

**true** si el **type** es compatible; de lo contrario, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [XmlResolver](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)