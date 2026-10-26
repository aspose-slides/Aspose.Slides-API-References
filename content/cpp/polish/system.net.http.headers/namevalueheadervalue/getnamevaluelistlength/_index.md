---
title: GetNameValueListLength()
second_title: Aspose.Slides - referencja API C++
description: Konwertuje podany ciąg znaków od określonego indeksu do kolekcji instancji klasy NameValueHeaderValue i zwraca długość przetworzonego podciągu.
type: docs
weight: 131
url: /pl/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) metoda

Konwertuje podany ciąg znaków od określonego indeksu do kolekcji instancji klasy NameValueHeaderValue i zwraca długość przetworzonego podciągu.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do analizy. |
| startIndex | **int32_t** | Pozycja początkowa do analizy. |
| delimiter | char16_t | Ciąg znaków używany do oddzielania elementów w określonym ciągu. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Parametr wyjściowy, do którego zostanie przypisana przetworzona kolekcja. |

### Wartość zwracana

Długość przetworzonego podciągu.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [ObjectCollection](../../objectcollection/)
* Klasa [NameValueHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)