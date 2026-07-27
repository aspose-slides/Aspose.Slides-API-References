---
title: GetEntity()
second_title: Referencia de la API de Aspose.Slides para C++
description: Asigna una URI a un objeto que contiene el recurso real.
type: docs
weight: 53
url: /es/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) método


Asigna una URI a un objeto que contiene el recurso real.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | La URI devuelta por la llamada a [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Actualmente no se usa. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | El tipo de objeto a devolver. La implementación actual sólo devuelve objetos Stream. |

### Valor devuelto

Un objeto stream o **nullptr** si se especifica un tipo distinto de stream.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [XmlUrlResolver](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)