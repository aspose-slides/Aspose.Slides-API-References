---
title: GetNameValueLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een opgegeven tekenreeks vanaf de gespecificeerde index naar een instantie van de NameValueHeaderValue klasse.
type: docs
weight: 118
url: /nl/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) methode

Converteert een opgegeven tekenreeks vanaf de gespecificeerde index naar een instantie van de [NameValueHeaderValue](../) klasse.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een tekenreeks om te parseren. |
| startIndex | **int32_t** | Een startpositie voor het parseren. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Een instantie waarin een geparseerd object zal worden toegewezen. |

### Retourwaarde

Retourneert de lengte van een geparseerde subreeks, anders 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) methode

Converteert een opgegeven tekenreeks vanaf de gespecificeerde index naar een instantie van de [NameValueHeaderValue](../) klasse.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een tekenreeks om te parseren. |
| startIndex | **int32_t** | Een startpositie voor het parseren. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Een functie die wordt gebruikt om nieuwe instanties van de [NameValueHeaderValue](../) klasse te maken. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Een instantie waarin een geparseerd object zal worden toegewezen. |

### Retourwaarde

Retourneert de lengte van een geparseerde subreeks, anders 0.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Klasse [String](../../../system/string/)
* Klasse [NameValueHeaderValue](../)
* Naamruimte [System::Net::Http::Headers](../../)
* Bibliotheek [Aspose.Slides](../../../)