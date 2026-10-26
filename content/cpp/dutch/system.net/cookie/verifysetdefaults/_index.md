---
title: VerifySetDefaults()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieert en stelt de standaardwaarden van het attribuut in.
type: docs
weight: 482
url: /nl/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) methode

Verifieert en stelt de standaardwaarden van het attribuut in.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | De specificatie van het cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De Uri-klasse-instantie die wordt gebruikt om de interne velden te initialiseren. |
| isLocalDomain | **bool** | Een waarde die aangeeft of het cookie in het lokale domein wordt geplaatst. |
| localDomain | [String](../../../system/string/) | Een lokale domeinnaam. |
| setDefault | **bool** | Een waarde die aangeeft of de attributen van het cookie moeten worden geïnitialiseerd met hun standaardwaarden. |
| shouldThrow | **bool** | Een waarde die aangeeft of er een uitzondering moet worden gegooid wanneer de opgegeven waarden ongeldig zijn. |

### Retourwaarde

True wanneer alle waarden geldig zijn, anders false.

## Zie ook

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [Cookie](../)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)