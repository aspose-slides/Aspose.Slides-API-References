---
title: SupportsType()
second_title: Aspose.Slides C++ API hivatkozás
description: Megállapítja, hogy a resolver támogat-e más Types-t, mint csak a Stream.
type: docs
weight: 66
url: /hu/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method


Megállapítja, hogy a resolver támogat-e más Types-t, mint csak a Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az ellenőrzendő abszolút URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó Type. |

### Visszatérési érték

**true** ha a Type támogatott; egyébként **false**.

## Kapcsolódó

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [XmlPreloadedResolver](../)
* Névtér [System::Xml::Resolvers](../../)
* Könyvtár [Aspose.Slides](../../../)