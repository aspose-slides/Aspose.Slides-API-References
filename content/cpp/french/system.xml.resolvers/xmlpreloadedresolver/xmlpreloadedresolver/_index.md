---
title: XmlPreloadedResolver()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe XmlPreloadedResolver.
type: docs
weight: 27
url: /fr/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructeur

Initialise une nouvelle instance de la classe [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructeur

Initialise une nouvelle instance de la classe [XmlPreloadedResolver](../) avec les DTD bien connus préchargés spécifiés.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Les DTD bien connus qui doivent être préremplis dans le cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructeur

Initialise une nouvelle instance de la classe [XmlPreloadedResolver](../) avec le résolveur de secours spécifié.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) ou votre propre résolveur. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructeur

Initialise une nouvelle instance de la classe [XmlPreloadedResolver](../) avec le résolveur de secours spécifié et les DTD bien connus préchargés.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) ou votre propre résolveur. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Les DTD bien connus qui doivent être préremplis dans le cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructeur

Initialise une nouvelle instance de la classe [XmlPreloadedResolver](../) avec le résolveur de secours spécifié, les DTD bien connus préchargés, et le comparateur d'égalité d'URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) ou votre propre résolveur. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Les DTD bien connus qui doivent être préremplis dans le cache. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | L'implémentation de l'interface IEqualityComparer à utiliser lors de la comparaison des URI. |

## Voir aussi

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)