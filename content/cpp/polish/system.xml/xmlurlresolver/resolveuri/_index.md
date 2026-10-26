---
title: ResolveUri()
second_title: Aspose.Slides dla C++ – Referencja API
description: Rozwiązuje bezwzględny URI na podstawie bazowego i względnego URI.
type: docs
weight: 66
url: /pl/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda

Rozwiązuje bezwzględny URI z bazowego i względnego URI.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Podstawowy URI używany do rozwiązywania względnego URI. |
| relativeUri | [String](../../../system/string/) | URI do rozwiązania. URI może być bezwzględny lub względny. Jeśli jest bezwzględny, ta wartość skutecznie zastępuje wartość **baseUri**. Jeśli jest względny, łączy się z **baseUri**, aby utworzyć bezwzględny URI. |

### Wartość zwracana

Bezwzględny URI lub **nullptr**, jeśli nie można rozwiązać względnego URI.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [XmlUrlResolver](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)