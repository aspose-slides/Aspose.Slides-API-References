---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior Aufzählung

Stellt das Verhalten bei der Behandlung der [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) Quelle (Datei oder **io.RawIOBase**) beim Laden und Arbeiten mit einer Instanz von [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) dar.

Der Typ PresentationLockingBehavior stellt die folgenden Mitglieder bereit:

## Felder

| Feld | Beschreibung |
| :- | :- |
| LOAD_AND_RELEASE | Die Quelle wird nur für die Dauer der Ausführung des [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) Konstruktors gesperrt.<br/>            Wenn [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/de/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) auf false gesetzt ist, werden alle BLOBs <br/>            in den Speicher geladen. Andernfalls können andere Mittel wie temporäre Dateien verwendet werden. Dieses Verhalten ist langsamer als [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/de/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), und wenn es möglich ist, das Eigentum an der Quelle an [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) zu übergeben, wird empfohlen, [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/de/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) zu verwenden. |
| KEEP_LOCKED | Die Quelle bleibt für die gesamte Lebensdauer der [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) Instanz gesperrt, bis sie <br/>            entsorgt wird.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/de/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) muss auf true gesetzt sein, um dieses Verhalten zu nutzen, sonst wird eine Ausnahme ausgelöst. Dieses Verhalten wird empfohlen, es ist schneller und verbraucht weniger Speicher als [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/de/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |

### Hinweise

Die Quelle ist der Parameter, der an den [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) Konstruktor übergeben wird. Im untenstehenden Beispiel ist die Quelle die Datei "pres.pptx".

Für dieses Beispiel wird die Quelle ("pres.pptx" Datei) für die Lebensdauer einer [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) Instanz gesperrt, d.h. sie kann von einem anderen Prozess nicht geändert oder gelöscht werden.

### Siehe auch
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)