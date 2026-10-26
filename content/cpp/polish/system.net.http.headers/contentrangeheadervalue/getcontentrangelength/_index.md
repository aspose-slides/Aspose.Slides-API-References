---
title: GetContentRangeLength()
second_title: Aspose.Slides dla C++ – Referencja API
description: Konwertuje podany ciąg znaków od określonej pozycji na instancję klasy ContentRangeHeaderValue.
type: docs
weight: 170
url: /pl/system.net.http.headers/contentrangeheadervalue/getcontentrangelength/
---
## ContentRangeHeaderValue::GetContentRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) method


Konwertuje przekazany ciąg znaków od określonej pozycji na instancję klasy [ContentRangeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do parsowania. |
| startIndex | **int32_t** | Pozycja początkowa do parsowania. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Instancja, w której zostanie przypisany sparsowany obiekt. |

### Wartość zwracana

Długość sparsowanego podciągu, w przeciwnym razie 0.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Object](../../../system/object/)
* Klasa [ContentRangeHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)