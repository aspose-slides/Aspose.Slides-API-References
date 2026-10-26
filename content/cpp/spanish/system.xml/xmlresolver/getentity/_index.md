---
title: GetEntity()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, asigna un URI a un objeto que contiene el recurso real.
type: docs
weight: 14
url: /es/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) método


Cuando se sobrescribe en una clase derivada, asigna un URI a un objeto que contiene el recurso real.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI devuelto por la llamada [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Actualmente no se usa. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | El tipo de objeto a devolver. La versión actual solo devuelve objetos Stream. |

### Valor de retorno

Un objeto stream o **nullptr** si se especifica un tipo distinto de stream.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [XmlResolver](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)