---
title: GetEntity()
second_title: Referencia de la API de Aspose.Slides para C++
description: Mapea un URI a un objeto que contiene el recurso real.
type: docs
weight: 27
url: /es/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) método

Mapea un URI a un objeto que contiene el recurso real.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI que se devuelve de la llamada [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Actualmente no se usa. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | El tipo de objeto a devolver. La versión actual solo devuelve objetos Stream. |

### Valor devuelto

El flujo devuelto al llamar a **GetEntity** sobre el [XmlResolver](../../xmlresolver/) subyacente. Si se especifica un tipo diferente de Stream, el método devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)