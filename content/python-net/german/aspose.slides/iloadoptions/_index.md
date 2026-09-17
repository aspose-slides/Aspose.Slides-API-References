---
title: ILoadOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iloadoptions/
---
## ILoadOptions Klasse

Ermöglicht das Angeben zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

Der ILoadOptions-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/de/aspose.slides/iloadoptions/load_format/) | Gibt das Format einer zu ladenden Präsentation zurück oder setzt es.<br/>            Lesen/Schreiben [`LoadFormat`](/slides/python-net/de/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides/iloadoptions/default_regular_font/) | Gibt die reguläre Schriftart zurück oder setzt sie, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen-Schreiben **str**. |
| [`default_symbol_font`](/slides/python-net/de/aspose.slides/iloadoptions/default_symbol_font/) | Gibt die Symbolschriftart zurück oder setzt sie, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen-Schreiben **str**. |
| [`default_asian_font`](/slides/python-net/de/aspose.slides/iloadoptions/default_asian_font/) | Gibt die asiatische Schriftart zurück oder setzt sie, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen-Schreiben **str**. |
| [`password`](/slides/python-net/de/aspose.slides/iloadoptions/password/) | Liest oder setzt das Kennwort.<br/>            Lesen-Schreiben **str**. |
| [`only_load_document_properties`](/slides/python-net/de/aspose.slides/iloadoptions/only_load_document_properties/) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist.<br/>            Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten <br/>            Präsentationsdatei geladen werden dürfen und das Passwort ignoriert wird.<br/>            Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen <br/>            Passwort geladen werden muss.<br/>            Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert immer ignoriert.<br/>            Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und der Eigenschaftswert true, dann<br/>            können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst.<br/>            Lesen-Schreiben **bool**. |
| [`warning_callback`](/slides/python-net/de/aspose.slides/iloadoptions/warning_callback/) | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang <br/>            fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/de/aspose.slides/iloadoptions/blob_management_options/) | Stellt die Optionen dar, die verwendet werden können, um das Verhalten beim Umgang mit Binary Large Objects (BLOBs) zu steuern,<br/>            beispielsweise durch die Verwendung temporärer Dateien oder der maximalen BLOB-Bytes im Speicher. Diese Optionen sollen das optimale Leistungs-/Speicherverbrauchs-Verhältnis für eine bestimmte Umgebung oder Anforderung einstellen.<br/>            Ein Binary Large Object (BLOB) ist ein Binärdatenobjekt, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann <br/>            ein Audio, Video oder die Präsentation selbst sein. |
| [`document_level_font_sources`](/slides/python-net/de/aspose.slides/iloadoptions/document_level_font_sources/) | Gibt die Quellen für externe Schriftarten an, die von der Präsentation verwendet werden.<br/>            Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt |
| [`interruption_token`](/slides/python-net/de/aspose.slides/iloadoptions/interruption_token/) | Der Token zur Überwachung von Unterbrechungsanfragen.<br/>            <br/>            Dieser Token verwaltet die gesamte Lebensdauer der [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation <br/>            wird durch Aufruf der [`IInterruptionTokenSource.interrupt`](/slides/python-net/de/aspose.slides/iinterruptiontokensource/interrupt) Methode des <br/>            [`IInterruptionTokenSource`](/slides/python-net/de/aspose.slides/iinterruptiontokensource) unterbrochen. |
| [`resource_loading_callback`](/slides/python-net/de/aspose.slides/iloadoptions/resource_loading_callback/) | Gibt das Callback-Interface zurück oder setzt es, das das Laden externer Ressourcen verwaltet.<br/>            Lesen/Schreiben [`IResourceLoadingCallback`](/slides/python-net/de/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/de/aspose.slides/iloadoptions/spreadsheet_options/) | Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenkalkulationsverhalten festzulegen. |
| [`default_text_language`](/slides/python-net/de/aspose.slides/iloadoptions/default_text_language/) | Gibt die Standardsprache für den Präsentationstext zurück oder setzt sie.<br/>             Lesen/Schreiben **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/de/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Bestimmt, ob Aspose.Slides beim Laden einer Präsentation alle eingebetteten Binärobjekte löschen wird.<br/>            <br/>Die Arten der eingebetteten Binärobjekte:<br/><br/><br/>* VBA-Projekt [`IPresentation.vba_project`](/slides/python-net/de/aspose.slides/ipresentation/vba_project)<br/>* OLE-Objekt-eingebettete Daten [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX-Steuerungs-Binärdaten [`IControl.active_x_control_binary`](/slides/python-net/de/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lesen/Schreiben **bool**. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)