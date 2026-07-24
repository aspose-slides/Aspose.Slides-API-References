---
title: "System::Drawing::Printing"
second_title: Aspose.Slides für C++ API Referenz
description: 
type: docs
weight: 521
url: /de/system.drawing.printing/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Margins](./margins/) | Stellt die Ränder einer gedruckten Seite dar. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [PageSettings](./pagesettings/) | Stellt die Einstellungen einer gedruckten Seite dar. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [PaperSize](./papersize/) | Gibt die Größe eines Papierblatts an. |
| [PrintController](./printcontroller/) | Steuert, wie ein Dokument gedruckt wird, wenn aus einer [Windows](../system.windows/) Forms-Anwendung gedruckt wird. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [PrintDocument](./printdocument/) | Sendet die Ausgabe an einen Drucker, wenn aus einer [Windows](../system.windows/) Forms-Anwendung gedruckt wird. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [PrinterResolution](./printerresolution/) | Stellt die Auflösung eines Druckers dar. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [PrinterSettings](./printersettings/) | Stellt die Einstellungen eines Druckers dar. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [PrintEventArgs](./printeventargs/) | Stellt Daten für die BeginPrint- und EndPrint-Ereignisse bereit. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [PrintPageEventArgs](./printpageeventargs/) | Stellt Daten für das PrintPage-Ereignis bereit. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [QueryPageSettingsEventArgs](./querypagesettingseventargs/) | Stellt Daten für das QueryPageSettings-Ereignis bereit. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |
| [StandardPrintController](./standardprintcontroller/) | Gibt einen Druckcontroller an, der Informationen an einen Drucker sendet. Objekte dieser Klasse sollten nur mithilfe der [System::MakeObject()](../system/makeobject/) Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies Laufzeitfehler und/oder Assertion-Fehler verursacht. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben. |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [PaperKind](./paperkind/) | Gibt die standardmäßigen Papiergrößen an. |
| [PrintAction](./printaction/) | Gibt einen Typ eines Druckvorgangs an. |
| [PrintRange](./printrange/) | Gibt an, welche Seiten gedruckt werden. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [PrintPageEventHandler](./printpageeventhandler/) | Ein Funktionstyp, der das PrintPage-Ereignis verarbeitet. |
| [PrintEventHandler](./printeventhandler/) | Ein Funktionsobjekt-Typ, der die BeginPrint- und EndPrint-Ereignisse verarbeitet. |