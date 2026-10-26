---
title: SupportsType()
second_title: Riferimento API di Aspose.Slides per C++
description: Consente al resolver di restituire tipi diversi da Stream.
type: docs
weight: 40
url: /it/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metodo

Consente al resolver di restituire tipi diversi da Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo da restituire. |

### Valore di ritorno

**true** se il **type** è supportato; altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)