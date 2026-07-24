---
title: GetEntity()
second_title: Aspose.Slides für C++ API Referenz
description: Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält.
type: docs
weight: 27
url: /de/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die URI, die vom Aufruf [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) zurückgegeben wird. |
| role | [String](../../../system/string/) | Zurzeit nicht verwendet. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ des zurückzugebenden Objekts. Die aktuelle Version gibt nur Stream-Objekte zurück. |

### Rückgabewert

Der Stream, der durch Aufruf von **GetEntity** auf dem zugrunde liegenden [XmlResolver](../../xmlresolver/) zurückgegeben wird. Wenn ein anderer Typ als Stream angegeben wird, gibt die Methode **nullptr** zurück.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlSecureResolver](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)