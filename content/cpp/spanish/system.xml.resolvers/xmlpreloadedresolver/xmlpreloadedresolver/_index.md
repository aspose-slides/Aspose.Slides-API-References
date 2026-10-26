---
title: XmlPreloadedResolver()
second_title: Referencia API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase XmlPreloadedResolver.
type: docs
weight: 27
url: /es/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructor

Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructor

Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con los DTD bien conocidos precargados especificados.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Los DTD bien conocidos que deben prepoblarse en la caché. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructor

Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con el resolver de respaldo especificado.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) o su propio resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructor

Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con el resolver de respaldo especificado y los DTD bien conocidos precargados.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) o su propio resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Los DTD bien conocidos que deben prepoblarse en la caché. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructor

Inicializa una nueva instancia de la clase [XmlPreloadedResolver](../) con el resolver de respaldo especificado, los DTD bien conocidos precargados y el comparador de igualdad de URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) o su propio resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Los DTD bien conocidos que deben prepoblarse en la caché. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | La implementación de la interfaz IEqualityComparer que se debe usar al comparar URIs. |

## Ver también

* Enumeración [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlPreloadedResolver](../)
* Clase [XmlResolver](../../../system.xml/xmlresolver/)
* Clase [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Clase [Uri](../../../system/uri/)
* Espacio de nombres [System::Xml::Resolvers](../../)
* Biblioteca [Aspose.Slides](../../../)