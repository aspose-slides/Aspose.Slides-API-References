---
title: GetEntity()
second_title: Referencia de API de Aspose.Slides para C++
description: Mapea un URI a un objeto que contiene el recurso real.
type: docs
weight: 53
url: /es/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) método


Mapea un URI a un objeto que contiene el recurso real.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI devuelto por la llamada a [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Actualmente no se usa. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | El tipo de objeto a devolver. El [XmlPreloadedResolver](../) admite objetos Stream y objetos TextReader para los URI que fueron añadidos como [String](../../../system/string/). Si el tipo solicitado no es compatible con el resolvedor, se lanzará una excepción. Utilice el método XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) para determinar si un **Type** determinado es compatible con este resolvedor. |

### Valor devuelto

Un objeto Stream o TextReader que corresponde a la fuente real.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [XmlPreloadedResolver](../)
* Espacio de nombres [System::Xml::Resolvers](../../)
* Biblioteca [Aspose.Slides](../../../)