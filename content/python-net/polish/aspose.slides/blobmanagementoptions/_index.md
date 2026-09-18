---
title: BlobManagementOptions class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions klasa

Reprezentuje opcje, które można wykorzystać do zarządzania regułami obsługi BLOB oraz innymi ustawieniami BLOB.

Typ BlobManagementOptions udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides/blobmanagementoptions/__init__/#) | Tworzy nowe domyślne opcje zarządzania blobami. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/pl/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Ta właściwość określa, czy wystąpienie klasy Presentation może być właścicielem źródła – pliku <br/>            lub strumienia podczas życia tego wystąpienia. Jeśli wystąpienie jest właścicielem, blokuje źródło. Pomaga to <br/>            poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) <br/>            nie może być zmieniane podczas życia wystąpienia Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/pl/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacząco <br/>            zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.<br/>            Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją. |
| [`temp_files_root_path`](/slides/python-net/pl/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. <br/>            Proces hostingowy powinien mieć uprawnienia do <br/>            tworzenia tam plików i folderów. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/pl/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y<br/>            są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (np. pliki<br/>            tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj<br/>            tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)