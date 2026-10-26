---
title: IBlobManagementOptions class
second_title: Aspose.Slides dla Pythona - referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions klasa

Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy byt – np. BLOB może być plikiem audio, wideo lub samą prezentacją. Stosuje się szereg technik optymalizujących zużycie pamięci podczas pracy z BLOB-ami – które już zostały zapisane w prezentacji lub zostaną dodane później programowo. Używając [`IBlobManagementOptions`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions) możesz zmienić różne aspekty zachowania dotyczące obsługi BLOB-ów dla czasu życia instancji [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation).

Typ IBlobManagementOptions udostępnia następujące członki:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku <br/>            lub strumienia podczas czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to <br/>            poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) <br/>            nie może być zmieniane w trakcie życia instancji Presentation. Jest to przykład: |
| [`is_temporary_files_allowed`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacząco <br/>            zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.<br/>            Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją. |
| [`temp_files_root_path`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. <br/>            Proces hostingowy musi mieć uprawnienia do <br/>            tworzenia tam plików i folderów. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y<br/>            są ładowane do pamięci; dopiero po przekroczeniu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań. |


### Zobacz także
* klasa [`IBlobManagementOptions`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions)
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)