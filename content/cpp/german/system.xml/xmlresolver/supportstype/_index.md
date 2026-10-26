---
title: SupportsType()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermöglicht dem Resolver, Typen zurückzugeben, die nicht Stream sind.
type: docs
weight: 40
url: /de/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) Methode

Ermöglicht dem Resolver, Typen zurückzugeben, die nicht Stream sind.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Der URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Der zurückzugebende Typ. |

### Rückgabewert

**true** wenn der **type** unterstützt wird; andernfalls **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlResolver](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)