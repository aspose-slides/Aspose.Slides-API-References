---
title: SupportsType()
second_title: Aspose.Slides per C++ Riferimento API
description: Determina se il resolver supporta altri Types oltre a Stream.
type: docs
weight: 66
url: /it/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method

Determina se il resolver supporta altri Tipi oltre a Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI assoluto da verificare. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Il Type da restituire. |

### Valore di ritorno

**true** se il Type è supportato; altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)