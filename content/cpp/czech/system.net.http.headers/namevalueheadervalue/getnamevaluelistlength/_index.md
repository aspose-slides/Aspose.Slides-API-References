---
title: GetNameValueListLength()
second_title: Aspose.Slides pro C++ – reference API
description: Převede předaný řetězec od zadaného indexu do kolekce instancí třídy NameValueHeaderValue a vrátí délku analyzovaného podřetězce.
type: docs
weight: 131
url: /cs/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) metoda

Převede předaný řetězec od zadaného indexu do kolekce instancí třídy NameValueHeaderValue a vrátí délku analyzovaného podřetězce.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k analýze. |
| startIndex | **int32_t** | Počáteční pozice pro analýzu. |
| delimiter | char16_t | Řetězec, který se používá k oddělení položek ve specifikovaném řetězci. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Výstupní parametr, do kterého bude přiřazena analyzovaná kolekce. |

### Návratová hodnota

Délka analyzovaného podřetězce.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [ObjectCollection](../../objectcollection/)
* Třída [NameValueHeaderValue](../)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)