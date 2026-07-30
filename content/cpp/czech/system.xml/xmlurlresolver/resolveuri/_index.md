---
title: ResolveUri()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Rozřeší absolutní URI ze základního a relativního URI.
type: docs
weight: 66
url: /cs/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda

Resolves the absolute URI from the base and relative URIs.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Základní URI používané k rozřešení relativního URI. |
| relativeUri | [String](../../../system/string/) | URI, které se má rozřešit. URI může být absolutní nebo relativní. Pokud je absolutní, tato hodnota efektivně nahradí hodnotu **baseUri**. Pokud je relativní, kombinuje se s **baseUri** a vytvoří absolutní URI. |

### Návratová hodnota

Absolutní URI nebo **nullptr**, pokud není možné rozřešit relativní URI.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [XmlUrlResolver](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)