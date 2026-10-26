---
title: GetEntity()
second_title: Referência da API Aspose.Slides para C++
description: Mapeia um URI para um objeto que contém o recurso real.
type: docs
weight: 27
url: /pt/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) método

Mapeia um URI para um objeto que contém o recurso real.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI que é retornado da chamada [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Atualmente não usado. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | O tipo de objeto a ser retornado. A versão atual retorna apenas objetos Stream. |

### Valor de Retorno

O fluxo retornado ao chamar **GetEntity** no [XmlResolver](../../xmlresolver/) subjacente. Se um tipo diferente de Stream for especificado, o método retorna **nullptr**.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)