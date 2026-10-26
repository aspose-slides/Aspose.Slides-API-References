---
title: LoadOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/loadoptions/
---
## LoadOptions Klasse

Ermöglicht das Angeben zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

Der Typ LoadOptions stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/loadoptions/__init__/#) | Erstellt neue Standard-Ladeoptionen. |
| [`__init__(self, load_format)`](/slides/python-net/de/aspose.slides/loadoptions/__init__/#loadformat) | Erstellt neue Ladeoptionen. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`load_format`](/slides/python-net/de/aspose.slides/loadoptions/load_format/) | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest.<br/>            Lesen/Schreiben [`LoadFormat`](/slides/python-net/de/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides/loadoptions/default_regular_font/) | Gibt die reguläre Schriftart zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`default_symbol_font`](/slides/python-net/de/aspose.slides/loadoptions/default_symbol_font/) | Gibt die Symbolschriftart zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`default_asian_font`](/slides/python-net/de/aspose.slides/loadoptions/default_asian_font/) | Gibt die asiatische Schriftart zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`password`](/slides/python-net/de/aspose.slides/loadoptions/password/) | Liest oder setzt das Passwort.<br/>            Lesen/Schreiben **str**. |
| [`only_load_document_properties`](/slides/python-net/de/aspose.slides/loadoptions/only_load_document_properties/) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist.<br/>            Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten <br/>            Präsentationsdatei geladen werden müssen und das Passwort ignoriert wird.<br/>            Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen <br/>            Passwort geladen werden muss.<br/>            Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert.<br/>            Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert true ist, dann<br/>            können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst.<br/>            Lesen/Schreiben **bool**. |
| [`warning_callback`](/slides/python-net/de/aspose.slides/loadoptions/warning_callback/) | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang <br/>            fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/de/aspose.slides/loadoptions/blob_management_options/) | Stellt die Optionen dar, mit denen das Verhalten beim Umgang mit Binary Large Objects (BLOBs) verwaltet werden kann,<br/>            beispielsweise die Verwendung temporärer Dateien oder maximaler BLOB-Bytes im Speicher. Diese Optionen sollen das optimale Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung festlegen.<br/>            Ein Binary Large Object (BLOB) ist ein Binärdatenblock, der als einzelne Einheit gespeichert wird – d. h. ein BLOB kann <br/>            ein Audio, Video oder die Präsentation selbst sein. |
| [`document_level_font_sources`](/slides/python-net/de/aspose.slides/loadoptions/document_level_font_sources/) | Gibt Quellen für externe Schriftarten an, die von der Präsentation verwendet werden sollen.<br/>            Diese Schriftarten stehen der Präsentation während ihrer gesamten Laufzeit zur Verfügung und werden nicht mit anderen Präsentationen geteilt. |
| [`interruption_token`](/slides/python-net/de/aspose.slides/loadoptions/interruption_token/) | Das Token zur Überwachung von Unterbrechungsanfragen.<br/>            <br/>            Dieses Token verwaltet die gesamte Laufzeit der [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)-Instanz. Jede langlaufende Operation, wie das Laden <br/>            oder Speichern einer Präsentation, wird durch Aufruf der [`InterruptionTokenSource.interrupt`](/slides/python-net/de/aspose.slides/interruptiontokensource/interrupt)-Methode des <br/>            [`InterruptionTokenSource`](/slides/python-net/de/aspose.slides/interruptiontokensource) unterbrochen. |
| [`resource_loading_callback`](/slides/python-net/de/aspose.slides/loadoptions/resource_loading_callback/) | Gibt die Callback-Schnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet.<br/>            Lesen/Schreiben [`IResourceLoadingCallback`](/slides/python-net/de/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/de/aspose.slides/loadoptions/spreadsheet_options/) | Liest Optionen für Tabellenkalkulationen. Beispielsweise beeinflussen diese Optionen die Berechnung von Formeln für Diagramme. |
| [`default_text_language`](/slides/python-net/de/aspose.slides/loadoptions/default_text_language/) | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/de/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.<br/>            <br/>Die Arten der eingebetteten Binärobjekte:<br/><br/><br/>* VBA-Projekt [`IPresentation.vba_project`](/slides/python-net/de/aspose.slides/ipresentation/vba_project)<br/>* OLE-Objekt eingebettete Daten [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX-Steuerung Binärdaten [`IControl.active_x_control_binary`](/slides/python-net/de/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lesen/Schreiben **bool**. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)