---
title: SupportsType()
second_title: Aspose.Slides C++ API referencia
description: Lehetővé teszi a resolver számára, hogy a Stream-etől eltérő típusokat adjon vissza.
type: docs
weight: 40
url: /hu/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metódus


Enables the resolver to return types other than Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó type. |

### Visszatérési érték

**true** ha a **type** támogatott; egyébként **false**.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [XmlResolver](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)