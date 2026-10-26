---
title: MakeDiff()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Oblicza 'diff' pomiędzy dwiema kolekcjami. Dla każdego elementu każdej kolekcji jako klucza wynikowa wartość będzie dodatnia, jeśli element występuje częściej w \"expected\" kolekcji, ujemna, jeśli element występuje częściej w \"actual\" kolekcji, oraz zero, jeśli element występuje równą liczbę razy w każdej kolekcji.
type: docs
weight: 1
url: /pl/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method

Oblicza 'diff' pomiędzy dwiema kolekcjami. Dla każdego elementu każdej kolekcji jako klucza wynikowa wartość będzie dodatnia, jeśli element występuje częściej w \"expected\" kolekcji, ujemna, jeśli element występuje częściej w \"actual\" kolekcji, oraz zero, jeśli element występuje równą liczbę razy w każdej kolekcji.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ elementu oczekiwanej kolekcji. |
| T2 | Typ elementu rzeczywistej kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Oczekiwana kolekcja. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Rzeczywista kolekcja. |

### Wartość zwracana

Mapa wyników porównania dla poszczególnych wartości zgodnie z powyższymi regułami.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Dictionary](../../../system.collections.generic/dictionary/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktura [CollectionAssertHelper](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)