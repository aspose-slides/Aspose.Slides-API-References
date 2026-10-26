---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides dla Pythona poprzez .NET API
description: 
type: docs
url: /pl/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory właściwość
Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

### Uwagi
Ta właściwość jest ignorowana, jeśli [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) jest ustawione na false, ponieważ pamięć jest wtedy jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOB-ów w pamięci nie ma wpływu.

### Definicja:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Zobacz także
* klasa [`IBlobManagementOptions`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)