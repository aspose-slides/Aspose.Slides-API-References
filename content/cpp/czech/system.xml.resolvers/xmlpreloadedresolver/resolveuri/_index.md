---
title: ResolveUri()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vyřeší absolutní URI ze základního a relativního URI.
type: docs
weight: 40
url: /cs/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda


Vyřeší absolutní URI ze základního a relativního URI.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Základní URI použité k vyřešení relativního URI. |
| relativeUri | [String](../../../system/string/) | URI k vyřešení. URI může být absolutní nebo relativní. Pokud je absolutní, tato hodnota efektivně nahrazuje hodnotu **baseUri**. Pokud je relativní, kombinuje se s **baseUri**, aby vytvořila absolutní URI. |

### Návratová hodnota

Objekt [Uri](../../../system/uri/) představující absolutní URI nebo **nullptr**, pokud relativní URI nelze vyřešit.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [XmlPreloadedResolver](../)
* Jmenný prostor [System::Xml::Resolvers](../../)
* Knihovna [Aspose.Slides](../../../)