---
title: CollectionsToMsg()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Serializuje dwie kolekcje w celu reprezentacji komunikatu.
type: docs
weight: 53
url: /pl/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String&, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>>&, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>>&) method

Serializuje dwie kolekcje do reprezentacji wiadomości.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ elementu oczekiwanej kolekcji. |
| T2 | Typ elementu rzeczywistej kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)& | Niestandardowy ciąg znaków wstawiany przed oczekiwaną wartością w wynikowej wiadomości |
| expected | const [System::SharedPtr](../../sharedptr/)<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)<T1>> & | Oczekiwana kolekcja. |
| actual | const [System::SharedPtr](../../sharedptr/)<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)<T2>> & | Rzeczywista kolekcja. |

### Wartość zwracana

Przyjazna dla użytkownika wiadomość o zawartości kolekcji.

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktura [CollectionAssertHelper](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)