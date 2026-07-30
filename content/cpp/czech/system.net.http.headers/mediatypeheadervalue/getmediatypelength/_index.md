---
title: GetMediaTypeLength()
second_title: Aspose.Slides pro C++ API referenci
description: Převede předaný řetězec od určeného indexu na instanci třídy MediaTypeHeaderValue.
type: docs
weight: 144
url: /cs/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) metoda

Převede předaný řetězec od určeného indexu na instanci třídy [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k analýze. |
| startIndex | **int32_t** | Počáteční pozice pro analýzu. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Delegát, který se používá k vytvoření instancí třídy [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Instance, do které bude přiřazen analyzovaný objekt. |

### Návratová hodnota

Vrací délku analyzovaného podřetězce, jinak 0.

## Viz také

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [MediaTypeHeaderValue](../)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)