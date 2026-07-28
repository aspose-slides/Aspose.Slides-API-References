---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBs mogą zajmować w pamięci. Domyślnie wszystkie BLOBs są ładowane do pamięci; dopiero po przekroczeniu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBs w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.
type: docs
weight: 92
url: /pl/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metoda

Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBy mogą zajmować w pamięci. Domyślnie wszystkie BLOBy są ładowane do pamięci; dopiero po przekroczeniu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBów w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego użycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Uwagi

Ta wartość jest ignorowana, jeśli [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) jest ustawione na false, ponieważ wtedy pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOBów w pamięci nie ma wpływu.

Domyślna wartość to 629,145,600 bajtów (600 MB).

Można ustawić tę właściwość na zero, ale nadal zostanie zarezerwowana niewielka minimalna ilość pamięci.

## Zobacz także

* Klasa [BlobManagementOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)