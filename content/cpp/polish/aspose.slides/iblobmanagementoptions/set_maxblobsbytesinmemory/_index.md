---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides dla C++ Referencja API
description: Definiuje maksymalny całkowity rozmiar (w bajtach), jaki wszystkie BLOBy mogą zajmować w pamięci. Domyślnie wszystkie BLOBy są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBów w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.
type: docs
weight: 92
url: /pl/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metoda


Definiuje maksymalny całkowity rozmiar (w bajtach), jaki wszystkie BLOBy mogą zajmować w pamięci. Domyślnie wszystkie BLOBy są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Uwagi

Ta wartość jest ignorowana, jeśli [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) jest ustawione na false, ponieważ pamięć jest wtedy jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOBów w pamięci nie ma efektu.

Domyślna wartość to 629,145,600 bajtów (600 MB).

Możesz ustawić tę właściwość na zero, ale niewielka minimalna ilość pamięci nadal będzie zarezerwowana.

## Zobacz także

* Klasa [IBlobManagementOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)