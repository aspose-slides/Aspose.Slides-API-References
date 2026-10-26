---
title: SupportsType()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el resolvedor admite otros Types además de Stream.
type: docs
weight: 66
url: /es/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) método

Determina si el resolvedor admite otros tipos además de Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI absoluto a comprobar. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | El Tipo a devolver. |

### Valor de retorno

**true** si el Tipo es compatible; de lo contrario, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [XmlPreloadedResolver](../)
* Espacio de nombres [System::Xml::Resolvers](../../)
* Biblioteca [Aspose.Slides](../../../)