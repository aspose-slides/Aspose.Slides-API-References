---
title: GetEntity()
second_title: Riferimento API di Aspose.Slides per C++
description: Associa un URI a un oggetto che contiene la risorsa reale.
type: docs
weight: 53
url: /it/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metodo

Associa un URI a un oggetto che contiene la risorsa reale.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI restituito dalla chiamata [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Attualmente non utilizzato. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo di oggetto da restituire. Il [XmlPreloadedResolver](../) supporta oggetti Stream e oggetti TextReader per gli URI aggiunti come [String](../../../system/string/). Se il tipo richiesto non è supportato dal resolver, verrà sollevata un'eccezione. Utilizzare il metodo XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) per determinare se un certo **Type** è supportato da questo resolver. |

### Valore restituito

Un oggetto Stream o TextReader che corrisponde alla fonte reale.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlPreloadedResolver](../)
* Spazio dei nomi [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)