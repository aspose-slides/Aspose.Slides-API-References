---
title: XmlPreloadedResolver()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe XmlPreloadedResolver.
type: docs
weight: 27
url: /pt/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() construtor

Inicializa uma nova instância da classe [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) construtor

Inicializa uma nova instância da classe [XmlPreloadedResolver](../) com os DTDs bem conhecidos pré-carregados especificados.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Os DTDs bem conhecidos que devem ser prepopulados no cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) construtor

Inicializa uma nova instância da classe [XmlPreloadedResolver](../) com o resolvedor de fallback especificado.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) ou seu próprio resolvedor. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) construtor

Inicializa uma nova instância da classe [XmlPreloadedResolver](../) com o resolvedor de fallback especificado e os DTDs bem conhecidos pré-carregados.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) ou seu próprio resolvedor. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Os DTDs bem conhecidos que devem ser prepopulados no cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) construtor

Inicializa uma nova instância da classe [XmlPreloadedResolver](../) com o resolvedor de fallback especificado, os DTDs bem conhecidos pré-carregados e o comparador de igualdade de URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) ou seu próprio resolvedor. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Os DTDs bem conhecidos que devem ser prepopulados no cache. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | A implementação da interface IEqualityComparer a ser usada ao comparar URIs. |

## Ver também

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlPreloadedResolver](../)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Classe [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Classe [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Biblioteca [Aspose.Slides](../../../)