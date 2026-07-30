---
title: ResolveUri()
second_title: Aspose.Slides pro C++ API Reference
description: Vyřeší absolutní URI ze základní a relativní URI voláním ResolveUri na podkladovém XmlResolveru.
type: docs
weight: 40
url: /cs/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda

Vyřeší absolutní URI ze základní a relativní URI voláním **ResolveUri** na podkladovém [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Základní URI použité k vyřešení relativní URI. |
| relativeUri | [String](../../../system/string/) | URI k vyřešení. URI může být absolutní nebo relativní. Pokud je absolutní, tato hodnota efektivně nahrazuje hodnotu **baseUri**. Pokud je relativní, kombinuje se s **baseUri**, aby vytvořila absolutní URI. |

### Návratová hodnota

Absolutní URI nebo **nullptr**, pokud relativní URI nelze vyřešit (vráceno voláním **ResolveUri** na podkladovém [XmlResolver](../../xmlresolver/)).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [XmlSecureResolver](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)