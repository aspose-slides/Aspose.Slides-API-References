---
title: GetRangeItemListLength()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Konwertuje podany ciąg znaków od określonej pozycji do kolekcji instancji klasy RangeItemHeaderValue.
type: docs
weight: 79
url: /pl/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) metoda

Konwertuje podany ciąg znaków od określonej pozycji do kolekcji instancji klasy RangeItemHeaderValue.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do parsowania. |
| startIndex | **int32_t** | Pozycja początkowa dla parsowania. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Instancja, w której zostanie przypisana sparsowana kolekcja. |

### Wartość zwracana

Długość sparsowanego podciągu, w przeciwnym razie 0.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [ICollection](../../../system.collections.generic/icollection/)
* Klasa [RangeItemHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)