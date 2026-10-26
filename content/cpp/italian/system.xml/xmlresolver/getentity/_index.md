---
title: GetEntity()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando viene sovrascritto in una classe derivata, mappa un URI a un oggetto che contiene la risorsa effettiva.
type: docs
weight: 14
url: /it/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metodo

When overridden in a derived class, maps a URI to an object that contains the actual resource.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI restituito dalla chiamata [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Attualmente non usato. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo di oggetto da restituire. La versione corrente restituisce solo oggetti Stream. |

### Valore restituito

Un oggetto stream o **nullptr** se è specificato un tipo diverso da stream.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlResolver](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)