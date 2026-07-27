---
title: GetEntity()
second_title: Referência da API Aspose.Slides para C++
description: Mapeia um URI para um objeto que contém o recurso real.
type: docs
weight: 53
url: /pt/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) método

Mapeia um URI para um objeto que contém o recurso real.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI retornado da chamada [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Atualmente não usado. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | O tipo de objeto a ser retornado. A implementação atual retorna apenas objetos Stream. |

### Valor de Retorno

Um objeto stream ou **nullptr** se for especificado um tipo diferente de stream.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)