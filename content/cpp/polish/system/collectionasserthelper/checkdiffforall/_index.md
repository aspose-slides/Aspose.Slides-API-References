---
title: CheckDiffForAll()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Sprawdza, czy wszystkie elementy kolekcji spełniają predykat.
type: docs
weight: 14
url: /pl/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method

Sprawdza, czy wszystkie elementy kolekcji spełniają predykat.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predykat do sprawdzenia. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Wartości do sprawdzenia. |

### Wartość zwracana

False, jeśli sprawdzenie nie powiedzie się dla któregokolwiek elementu, true, jeśli wszystkie przejdą.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [ICollection](../../../system.collections.generic/icollection/)
* Struktura [CollectionAssertHelper](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)