---
title: GetNameValueListLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een meegegeven string vanaf de opgegeven index naar de collectie van de NameValueHeaderValue-klasse-instanties en retourneert de lengte van een geparseerde substring.
type: docs
weight: 131
url: /nl/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) methode

Converteert een meegegeven String vanaf de opgegeven index naar de collectie van de NameValueHeaderValue-klasse-instanties en retourneert de lengte van een geparseerde substring.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een string om te analyseren. |
| startIndex | **int32_t** | Een startpositie voor analyse. |
| delimiter | char16_t | Een string die wordt gebruikt om items in de opgegeven string te scheiden. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | De uitvoerparameter waar een geparseerde collectie aan wordt toegewezen. |

### Retourwaarde

De lengte van een geparseerde substring.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)