---
title: GetMediaTypeLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een doorgegeven string vanaf de opgegeven index naar een instantie van de MediaTypeHeaderValue klasse.
type: docs
weight: 144
url: /nl/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) methode

Converteert een doorgegeven string vanaf de opgegeven index naar een instantie van de [MediaTypeHeaderValue](../) klasse.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een string om te parseren. |
| startIndex | **int32_t** | Een startpositie voor het parseren. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | De gedelegeerde die wordt gebruikt om instanties van de [MediaTypeHeaderValue](../) klasse te maken. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Een instantie waarin een geparseerd object zal worden toegewezen. |

### Retourwaarde

Retourneert de lengte van een geparseerde substring, anders 0.

## Zie ook

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Bibliotheek [Aspose.Slides](../../../)