---
title: SupportsType()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se o resolvedor suporta outros Types além de apenas Stream.
type: docs
weight: 66
url: /pt/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) método

Determina se o resolvedor suporta outros tipos além de apenas Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI absoluto a ser verificado. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | O Type a ser retornado. |

### Valor de Retorno

**true** se o Type for suportado; caso contrário, **false**.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)