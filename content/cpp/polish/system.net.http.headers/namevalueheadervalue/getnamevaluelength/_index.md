---
title: GetNameValueLength()
second_title: Aspose.Slides dla C++ Referencja API
description: Konwertuje przekazany ciąg od określonego indeksu na instancję klasy NameValueHeaderValue.
type: docs
weight: 118
url: /pl/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) metoda


Konwertuje przekazany ciąg od określonego indeksu na instancję klasy [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg do analizy. |
| startIndex | **int32_t** | Pozycja początkowa do analizy. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Instancja, w której zostanie przypisany sparsowany obiekt. |

### Wartość zwracana

Zwraca długość sparsowanego podciągu, w przeciwnym razie 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) metoda


Konwertuje przekazany ciąg od określonego indeksu na instancję klasy [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg do analizy. |
| startIndex | **int32_t** | Pozycja początkowa do analizy. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Funkcja używana do tworzenia nowych instancji klasy [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Instancja, w której zostanie przypisany sparsowany obiekt. |

### Wartość zwracana

Zwraca długość sparsowanego podciągu, w przeciwnym razie 0.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Klasa [String](../../../system/string/)
* Klasa [NameValueHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)