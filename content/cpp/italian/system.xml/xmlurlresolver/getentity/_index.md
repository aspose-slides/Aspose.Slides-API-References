---
title: GetEntity()
second_title: Riferimento API di Aspose.Slides per C++
description: Mappa un URI a un oggetto che contiene la risorsa effettiva.
type: docs
weight: 53
url: /it/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metodo

Mappa un URI a un oggetto che contiene la risorsa effettiva.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI restituito dalla chiamata [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Attualmente non utilizzato. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo di oggetto da restituire. L'implementazione attuale restituisce solo oggetti Stream. |

### Valore di ritorno

Un oggetto stream o **nullptr** se viene specificato un tipo diverso da stream.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlUrlResolver](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)