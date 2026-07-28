---
title: ResolveUri()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Rozwiązuje bezwzględny URI z podstawowego i względnego URI, wywołując ResolveUri na podstawowym XmlResolver.
type: docs
weight: 40
url: /pl/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda


Rozwiązuje bezwzględny URI z podstawowego i względnego URI, wywołując **ResolveUri** na podstawowym [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Podstawowy URI używany do rozwiązywania względnego URI. |
| relativeUri | [String](../../../system/string/) | URI do rozwiązania. URI może być bezwzględny lub względny. Jeśli jest bezwzględny, ta wartość efektywnie zastępuje wartość **baseUri**. Jeśli jest względny, łączy się z **baseUri**, tworząc bezwzględny URI. |

### Wartość zwracana

Bezwzględny URI lub **nullptr**, jeśli nie można rozwiązać względnego URI (zwracany po wywołaniu **ResolveUri** na podstawowym [XmlResolver](../../xmlresolver/)).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSecureResolver](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)