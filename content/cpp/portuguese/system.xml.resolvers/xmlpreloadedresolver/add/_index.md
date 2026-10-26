---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um array de bytes ao armazenamento XmlPreloadedResolver e o mapeia para um URI. Se o armazenamento já contém um mapeamento para o mesmo URI, o mapeamento existente é sobrescrito.
type: docs
weight: 79
url: /pt/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) método

Adiciona um array de bytes ao armazenamento [XmlPreloadedResolver](../) e o associa a um URI. Se o armazenamento já contém um mapeamento para o mesmo URI, o mapeamento existente será sobrescrito.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | O URI dos dados que está sendo adicionado ao armazenamento [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Um array de bytes com os dados que correspondem ao URI fornecido. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Adiciona um array de bytes ao armazenamento [XmlPreloadedResolver](../) e o associa a um URI. Se o armazenamento já contém um mapeamento para o mesmo URI, o mapeamento existente será sobrescrito.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | O URI dos dados que está sendo adicionado ao armazenamento [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Um array de bytes com os dados que correspondem ao URI fornecido. |
| offset | **int32_t** | O deslocamento no array de bytes fornecido onde os dados começam. |
| count | **int32_t** | O número de bytes a ler do array de bytes, a partir do deslocamento fornecido. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) método

Adiciona um Stream ao armazenamento [XmlPreloadedResolver](../) e o associa a um URI. Se o armazenamento já contém um mapeamento para o mesmo URI, o mapeamento existente será sobrescrito.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | O URI dos dados que está sendo adicionado ao armazenamento [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Um Stream com os dados que correspondem ao URI fornecido. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) método

Adiciona uma string com dados pré-carregados ao armazenamento [XmlPreloadedResolver](../) e a associa a um URI. Se o armazenamento já contém um mapeamento para o mesmo URI, o mapeamento existente será sobrescrito.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | O URI dos dados que está sendo adicionado ao armazenamento [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | Um [String](../../../system/string/) com os dados que correspondem ao URI fornecido. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)