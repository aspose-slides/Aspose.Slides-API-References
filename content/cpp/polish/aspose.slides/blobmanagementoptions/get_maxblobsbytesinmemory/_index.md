---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides dla C++ - referencja API
description: Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBs mogą zajmować w pamięci. Domyślnie wszystkie BLOBs są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBs w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.
type: docs
weight: 79
url: /pl/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() metoda

Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBs mogą zajmować w pamięci. Domyślnie wszystkie BLOBs są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBs w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Uwagi

Ta wartość jest ignorowana, jeśli [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) jest ustawione na false, ponieważ pamięć jest wtedy jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOB w pamięci nie przynosi efektu.

Domyślna wartość to 629,145,600 bajtów (600 MB).

Możesz ustawić tę właściwość na zero, ale niewielka minimalna ilość pamięci nadal będzie zarezerwowana.

## Zobacz także

* Klasa [BlobManagementOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)