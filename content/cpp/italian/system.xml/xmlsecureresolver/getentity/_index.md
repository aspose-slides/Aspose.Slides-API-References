---
title: GetEntity()
second_title: Riferimento API di Aspose.Slides per C++
description: Associa un URI a un oggetto che contiene la risorsa effettiva.
type: docs
weight: 27
url: /it/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Associa un URI a un oggetto che contiene la risorsa effettiva.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI restituito dalla chiamata [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Attualmente non utilizzato. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo di oggetto da restituire. La versione corrente restituisce solo oggetti Stream. |

## Valore di ritorno

Il flusso restituito chiamando **GetEntity** sull'[XmlResolver](../../xmlresolver/) sottostante. Se viene specificato un tipo diverso da Stream, il metodo restituisce **nullptr**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)