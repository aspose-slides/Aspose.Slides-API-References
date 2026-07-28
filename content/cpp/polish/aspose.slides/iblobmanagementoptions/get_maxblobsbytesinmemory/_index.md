---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB mogą zajmować w pamięci. Domyślnie wszystkie BLOB są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.
type: docs
weight: 79
url: /pl/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() metoda

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBs mogą zajmować w pamięci. Domyślnie wszystkie BLOBs są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBs w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Uwagi

Ta wartość jest ignorowana, jeśli [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) jest ustawione na false, ponieważ pamięć jest wtedy jedynym dostępnym miejscem przechowywania i ograniczanie użycia BLOB w pamięci nie ma efektu.

Domyślna wartość to 629,145,600 bajtów (600 MB).

Możesz ustawić tę właściwość na zero, ale niewielka minimalna ilość pamięci będzie nadal rezerwowana.

## Zobacz także

* Klasa [IBlobManagementOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)