---
title: IBlobManagementOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions Klasse

Ein Binary Large Object (BLOB) ist ein binärer Datensatz, der als einzelne Einheit gespeichert wird - d. h. BLOB kann ein 
            Audio, Video oder die Präsentation selbst sein. Eine Reihe von Techniken wird verwendet, um den Speicherverbrauch 
            beim Arbeiten mit BLOBs zu optimieren – die bereits in der Präsentation gespeichert ist oder später programmgesteuert hinzugefügt werden kann. 
            Mit [`IBlobManagementOptions`](/slides/python-net/de/aspose.slides/iblobmanagementoptions) können Sie verschiedene Verhaltensaspekte im Umgang mit BLOBs 
            für die Laufzeit des [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)-Objekts ändern.

Der IBlobManagementOptions-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/de/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quell-Datei <br/>            oder des Streams während der Lebensdauer der Instanz sein kann. Ist die Instanz Eigentümer, sperrt sie die Quelle. Dies hilft <br/>            den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) <br/>            kann während der Lebensdauer der Presentation-Instanz nicht geändert werden. Dies ist ein Beispiel: |
| [`is_temporary_files_allowed`](/slides/python-net/de/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Diese Eigenschaft definiert, ob temporäre Dateien beim Arbeiten mit BLOBs erstellt werden können, was den Speicherverbrauch stark <br/>            reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert.<br/>            Alle Dateien werden gelöscht, nachdem die Arbeit mit der Präsentation abgeschlossen ist. |
| [`temp_files_root_path`](/slides/python-net/de/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Der Root-Pfad, in dem temporäre Dateien erstellt werden. Das System-Temp-Verzeichnis wird standardmäßig verwendet. <br/>            Der Host-Prozess sollte die Berechtigung haben, <br/>            dort Dateien und Ordner zu erstellen. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/de/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Definiert die maximale Gesamtkapazität (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs<br/>            in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre<br/>            Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann aber zu hohem Speicherverbrauch führen. Verwenden Sie<br/>            diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen. |


### Siehe auch
* Klasse [`IBlobManagementOptions`](/slides/python-net/de/aspose.slides/iblobmanagementoptions)
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)