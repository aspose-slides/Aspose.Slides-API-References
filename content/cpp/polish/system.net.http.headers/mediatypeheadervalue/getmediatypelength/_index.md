---
title: GetMediaTypeLength()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy MediaTypeHeaderValue.
type: docs
weight: 144
url: /pl/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) metoda

Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do przetworzenia. |
| startIndex | **int32_t** | Pozycja początkowa do przetwarzania. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Delegat używany do tworzenia instancji klasy [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Instancja, do której zostanie przypisany przetworzony obiekt. |

### Wartość zwracana

Zwraca długość przetworzonego podciągu, w przeciwnym razie 0.

## Zobacz także

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [MediaTypeHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)