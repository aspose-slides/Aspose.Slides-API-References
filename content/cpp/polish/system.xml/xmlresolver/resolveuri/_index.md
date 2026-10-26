---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Reference
description: Gdy zostanie przesłonięta w klasie pochodnej, rozwiązuje bezwzględny URI z bazowego i względnego URI.
type: docs
weight: 27
url: /pl/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) metoda

Gdy zostanie przesłonięta w klasie pochodnej, rozwiązuje bezwzględny URI z bazowego i względnego URI.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Podstawowy URI używany do rozwiązania względnego URI. |
| relativeUri | [String](../../../system/string/) | URI do rozwiązania. URI może być bezwzględny lub względny. Jeśli jest bezwzględny, ta wartość efektywnie zastępuje wartość **baseUri**. Jeśli jest względny, łączy się z **baseUri**, aby utworzyć bezwzględny URI. |

### Wartość zwracana

Bezwzględny URI lub **nullptr**, jeśli nie można rozwiązać względnego URI.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [XmlResolver](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)