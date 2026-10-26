---
title: VerifySetDefaults()
second_title: Aspose.Slides för C++ API-referens
description: Verifierar och sätter standardattributens värden.
type: docs
weight: 482
url: /sv/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) metod

Verifierar och sätter standardattributens värden.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Kakans specifikation. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Instansen av Uri-klassen som används för att initiera de interna fälten. |
| isLocalDomain | **bool** | Ett värde som anger om kakan placeras i den lokala domänen. |
| localDomain | [String](../../../system/string/) | Ett lokalt domännamn. |
| setDefault | **bool** | Ett värde som anger om kakans attribut måste initieras med sina standardvärden. |
| shouldThrow | **bool** | Ett värde som anger om ett undantag ska kastas när de angivna värdena är ogiltiga. |

### Returvärde

Sant när alla värden är giltiga, annars falskt.

## Se även

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [Cookie](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)