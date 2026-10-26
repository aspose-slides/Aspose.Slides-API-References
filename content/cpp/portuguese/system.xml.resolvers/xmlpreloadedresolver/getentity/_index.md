---
title: GetEntity()
second_title: Referência da API Aspose.Slides para C++
description: Mapeia um URI para um objeto que contém o recurso real.
type: docs
weight: 53
url: /pt/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) método

Mapeia um URI para um objeto que contém o recurso real.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI retornado da chamada [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Atualmente não utilizado. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | O tipo de objeto a ser retornado. O [XmlPreloadedResolver](../) suporta objetos Stream e objetos TextReader para URIs que foram adicionados como [String](../../../system/string/). Se o tipo solicitado não for suportado pelo resolvedor, uma exceção será lançada. Use o método XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) para determinar se um determinado **Tipo** é suportado por este resolvedor. |

### Valor de Retorno

Um objeto Stream ou TextReader que corresponde à fonte real.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlPreloadedResolver](../)
* namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)