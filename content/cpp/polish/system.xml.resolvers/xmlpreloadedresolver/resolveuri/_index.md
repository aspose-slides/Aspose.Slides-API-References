---
title: ResolveUri()
second_title: Odwołanie API Aspose.Slides dla C++
description: Rozwiązuje pełny URI na podstawie bazowego i względnego URI.
type: docs
weight: 40
url: /pl/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda


Rozwiązuje pełny URI na podstawie bazowego i względnego URI.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Bazowy URI używany do rozwiązywania względnego URI. |
| relativeUri | [String](../../../system/string/) | URI do rozwiązania. URI może być bezwzględny lub względny. Jeśli jest bezwzględny, ta wartość skutecznie zastępuje wartość **baseUri**. Jeśli jest względny, łączy się z **baseUri**, aby utworzyć bezwzględny URI. |

### Wartość zwracana

Obiekt [Uri](../../../system/uri/) reprezentujący pełny URI lub **nullptr**, jeśli nie można rozwiązać względnego URI.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [XmlPreloadedResolver](../)
* Przestrzeń nazw [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)