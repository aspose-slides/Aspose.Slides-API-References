---
title: BlobManagementOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions Klasse

Stellt Optionen dar, die verwendet werden können, um BLOB-Verarbeitungsregeln und andere BLOB-Einstellungen zu verwalten.

Der BlobManagementOptions-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Constructor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/blobmanagementoptions/__init__/#) | Erstellt neue standardmäßige Blob-Verwaltungsoptionen. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/de/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Dieses Property definiert, ob eine Instanz der Presentation Klasse Eigentümer der Quell-Datei <br/>            oder des Streams während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Dies hilft <br/>            den Speicherverbrauch und die Leistung bei der Arbeit mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) <br/>            kann während der Lebensdauer der Presentation-Instanz nicht geändert werden. |
| [`is_temporary_files_allowed`](/slides/python-net/de/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Dieses Property definiert, ob temporäre Dateien während der Arbeit mit BLOBs erstellt werden können, was den Speicherverbrauch stark <br/>            reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert.<br/>            Alle Dateien werden gelöscht, nachdem die Arbeit mit der Präsentation abgeschlossen ist. |
| [`temp_files_root_path`](/slides/python-net/de/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Der Stammpfad, in dem temporäre Dateien erstellt werden. Das System-Temp-Verzeichnis wird standardmäßig verwendet. <br/>            Der Host-Prozess sollte über Berechtigungen zum <br/>            Erstellen von Dateien und Ordnern dort verfügen. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/de/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs<br/>            in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre<br/>            Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie<br/>            dieses Property, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)