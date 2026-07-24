---
title: GetEntity()
second_title: Aspose.Slides für C++ API-Referenz
description: Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält.
type: docs
weight: 53
url: /de/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) Methode


Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Der von [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) zurückgegebene URI. |
| role | [String](../../../system/string/) | Derzeit nicht verwendet. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ des zurückzugebenden Objekts. Die aktuelle Implementierung gibt nur Stream-Objekte zurück. |

### Rückgabewert

Ein Stream-Objekt oder **nullptr**, wenn ein Typ angegeben wird, der nicht Stream ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlUrlResolver](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)