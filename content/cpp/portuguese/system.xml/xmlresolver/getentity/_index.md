---
title: GetEntity()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, mapeia um URI para um objeto que contém o recurso real.
type: docs
weight: 14
url: /pt/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Quando sobrescrito em uma classe derivada, mapeia um URI para um objeto que contém o recurso real.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI retornado da chamada [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Atualmente não usado. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | O tipo de objeto a ser retornado. A versão atual retorna apenas objetos Stream. |

### Valor de Retorno

Um objeto stream ou **nullptr** se for especificado um tipo diferente de stream.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)