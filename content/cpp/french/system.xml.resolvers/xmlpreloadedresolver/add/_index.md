---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un tableau d'octets au magasin XmlPreloadedResolver et le mappe à une URI. Si le magasin contient déjà une correspondance pour la même URI, la correspondance existante est remplacée.
type: docs
weight: 79
url: /fr/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) méthode

Ajoute un tableau d'octets au magasin [XmlPreloadedResolver](../) et le mappe à une URI. Si le magasin contient déjà une correspondance pour la même URI, la correspondance existante est remplacée.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array with the data that corresponds to the provided URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Ajoute un tableau d'octets au magasin [XmlPreloadedResolver](../) et le mappe à une URI. Si le magasin contient déjà une correspondance pour la même URI, la correspondance existante est remplacée.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array with the data that corresponds to the provided URI. |
| offset | **int32_t** | The offset in the provided byte array where the data starts. |
| count | **int32_t** | The number of bytes to read from the byte array, starting at the provided offset. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) méthode

Ajoute un flux au magasin [XmlPreloadedResolver](../) et le mappe à une URI. Si le magasin contient déjà une correspondance pour la même URI, la correspondance existante est remplacée.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A Stream with the data that corresponds to the provided URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) méthode

Ajoute une chaîne avec des données préchargées au magasin [XmlPreloadedResolver](../) et la mappe à une URI. Si le magasin contient déjà une correspondance pour la même URI, la correspondance existante est remplacée.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [String](../../../system/string/)\& | Un [String](../../../system/string/) contenant les données correspondant à l'URI fournie. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)