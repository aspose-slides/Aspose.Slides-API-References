---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory właściwość
Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBy mogą zajmować w pamięci. Domyślnie wszystkie BLOBy
            są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (np. pliki tymczasowe)
            . Przechowywanie BLOBów w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj
            tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.


### Uwagi

Ta właściwość jest ignorowana, jeśli [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pl/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) jest ustawione na false, ponieważ wówczas pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOBów w pamięci nie ma wpływu.

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
* klasa [`BlobManagementOptions`](/slides/python-net/pl/aspose.slides/blobmanagementoptions)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)