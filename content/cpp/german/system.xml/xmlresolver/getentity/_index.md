---
title: GetEntity()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, ordnet sie eine URI einem Objekt zu, das die eigentliche Ressource enthält.
type: docs
weight: 14
url: /de/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, ordnet sie eine URI einem Objekt zu, das die eigentliche Ressource enthält.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die von [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/)-Aufruf zurückgegebene URI. |
| role | [String](../../../system/string/) | Derzeit nicht verwendet. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ des zurückzugebenden Objekts. Die aktuelle Version gibt nur Stream-Objekte zurück. |

### Rückgabewert

Ein Stream-Objekt oder **nullptr**, wenn ein anderer Typ als Stream angegeben wird.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlResolver](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)