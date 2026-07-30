---
title: GetNameValueLength()
second_title: Aspose.Slides pro C++ API Reference
description: Převede předaný řetězec od zadaného indexu na instanci třídy NameValueHeaderValue.
type: docs
weight: 118
url: /cs/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) metoda


Převede předaný řetězec od zadaného indexu na instanci třídy [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k parsování. |
| startIndex | **int32_t** | Počáteční pozice pro parsování. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Instance, do které bude přiřazen parsovaný objekt. |

### Návratová hodnota

Vrací délku parsovaného podřetězce, jinak 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) metoda


Převede předaný řetězec od zadaného indexu na instanci třídy [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k parsování. |
| startIndex | **int32_t** | Počáteční pozice pro parsování. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Funkce používaná k vytvoření nových instancí třídy [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Instance, do které bude přiřazen parsovaný objekt. |

### Návratová hodnota

Vrací délku parsovaného podřetězce, jinak 0.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Třída [String](../../../system/string/)
* Třída [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)