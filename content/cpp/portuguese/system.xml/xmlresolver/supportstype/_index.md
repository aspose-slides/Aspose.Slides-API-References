---
title: SupportsType()
second_title: Referência da API Aspose.Slides para C++
description: Permite que o resolvedor retorne tipos diferentes de Stream.
type: docs
weight: 40
url: /pt/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) método

Permite que o resolvedor retorne tipos diferentes de Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | O tipo a ser retornado. |

### Valor de Retorno

**true** se o **type** for suportado; caso contrário, **false**.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlResolver](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)