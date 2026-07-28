---
title: CollectionAssertHelper
second_title: Referencja API Aspose.Slides dla C++
description: Heler API do operacji związanych z kolekcjami.
type: docs
weight: 1548
url: /pl/system/collectionasserthelper/
---
## CollectionAssertHelper struct


Heler API dla operacji związanych z kolekcjami.

```cpp
class CollectionAssertHelper
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Sprawdza, czy wszystkie elementy kolekcji spełniają predykat. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Sprawdza, czy dowolny element kolekcji spełnia predykat. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serializuje dwie kolekcje do reprezentacji komunikatu. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Konwertuje kolekcję na łańcuch, łącząc reprezentacje tekstowe elementów. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Oblicza 'diff' między dwiema kolekcjami. Dla każdego elementu każdej kolekcji jako klucza wynikowa wartość będzie dodatnia, jeśli element występuje częściej w \"expected\" kolekcji, ujemna, jeśli element występuje częściej w \"actual\" kolekcji, oraz zero, jeśli element występuje taką samą liczbę razy w obu kolekcjach. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formatuje łańcuch, który ma być użyty jako tekst komunikatu. |
## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)