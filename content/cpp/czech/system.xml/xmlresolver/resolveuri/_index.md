---
title: ResolveUri()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Když je v odvozené třídě přepsáno, vrací absolutní URI ze základního a relativních URI.
type: docs
weight: 27
url: /cs/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda


Když je přepsáno v odvozené třídě, vrací absolutní URI ze základního a relativních URI.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Základní URI používané k vyřešení relativního URI. |
| relativeUri | [String](../../../system/string/) | URI, který se má vyřešit. URI může být absolutní nebo relativní. Pokud je absolutní, tato hodnota efektivně nahrazuje hodnotu **baseUri**. Pokud je relativní, kombinuje se s **baseUri** a vytvoří absolutní URI. |

### Návratová hodnota

Absolutní URI nebo **nullptr**, pokud nelze relativní URI vyřešit.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [XmlResolver](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)