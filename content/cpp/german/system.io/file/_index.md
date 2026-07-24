---
title: File
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Methoden zum Manipulieren von Dateien bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 261
url: /de/system.io/file/
---
## File Klasse

Stellt Methoden zum Manipulieren von Dateien bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class File
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Fügt Zeichenketten aus der angegebenen Zeichenketten-Sammlung in die angegebene Datei ein, wobei die angegebene Kodierung verwendet wird, indem jede Zeichenkette in einer neuen Zeile geschrieben wird. Wenn die angegebene Datei nicht existiert, wird sie erstellt. Die Datei wird nach dem Schreiben aller Zeichenketten geschlossen. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Fügt die angegebene Zeichenkette in die angegebene Datei ein, wobei die angegebene Kodierung verwendet wird. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Erstellt ein [StreamWriter](../streamwriter/)-Objekt, das Text an die angegebene Datei anhängt und UTF-8-Kodierung verwendet. Wenn die angegebene Datei nicht existiert, wird sie erstellt. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Kopiert die angegebene Datei an den angegebenen Speicherort. Wenn die Zieldatei bereits existiert, gibt ein Parameter an, ob sie überschrieben werden soll. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Erstellt eine neue Datei (oder überschreibt eine bestehende) und öffnet sie für Lese- und Schreibzugriff unter Verwendung der angegebenen Puffergröße und Optionen. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Erstellt eine neue oder öffnet eine bestehende Datei zum Schreiben von UTF-8-kodiertem Text. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NICHT IMPLEMENTIERT. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Löscht die angegebene Datei oder das Verzeichnis. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NICHT IMPLEMENTIERT. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Ermittelt, ob der angegebene Pfad auf eine vorhandene Datei verweist. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Gibt die Attribute der angegebenen Entität zurück. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Gibt die Erstellungszeit der angegebenen Entität als lokale Zeit zurück. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Gibt die Erstellungszeit der angegebenen Entität als UTC-Zeit zurück. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Gibt die letzte Zugriffszeit der angegebenen Entität als lokale Zeit zurück. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Gibt die letzte Zugriffszeit der angegebenen Entität als UTC-Zeit zurück. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Gibt die letzte Schreibzeit der angegebenen Entität als lokale Zeit zurück. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Gibt die letzte Schreibzeit der angegebenen Entität als UTC-Zeit zurück. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Verschiebt die angegebene Datei an den neuen Speicherort. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Öffnet die angegebene Datei im angegebenen Modus zum Lesen und Schreiben ohne Freigabe. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Öffnet die angegebene Datei im angegebenen Modus mit dem angegebenen Zugriffstyp und Freigabeoption. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Öffnet die angegebene Datei nur zum Lesen, im Modus 'Open' mit gemeinsamem Lesezugriff. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Öffnet die angegebene vorhandene Datei zum Lesen von Text mit UTF-8-Kodierung ohne Freigabe. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Öffnet die angegebene Datei nur zum Schreiben, im Modus 'OpenOrCreate' ohne Freigabe. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Liest den Inhalt der angegebenen Binärdatei in ein Byte-Array. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Liest den Inhalt der angegebenen Textdatei zeilenweise in ein Array von Zeichenketten unter Verwendung der angegebenen Zeichenkodierung. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Liest den Inhalt der angegebenen Textdatei in ein einzelnes [String](../../system/string/)-Objekt unter Verwendung der angegebenen Zeichenkodierung. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Liest den Inhalt der angegebenen Textdatei zeilenweise unter Verwendung der angegebenen Zeichenkodierung und gibt eine aufzählbare Sammlung von Zeichenketten zurück, von denen jede eine einzelne Zeile des Dateiinhalts darstellt. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Ersetzt den Inhalt einer Datei durch eine andere und erstellt ein Backup der ersetzten Datei. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Setzt die angegebenen Attribute für die angegebene Datei. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NICHT IMPLEMENTIERT. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NICHT IMPLEMENTIERT. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NICHT IMPLEMENTIERT. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NICHT IMPLEMENTIERT. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der angegebenen Entität auf die lokale Zeit. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der angegebenen Entität auf UTC-Zeit. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Überschreibt die angegebene Binärdatei und schreibt die angegebenen Bytes hinein. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Erstellt eine neue Textdatei oder überschreibt die bestehende und schreibt alle Zeichenketten aus der angegebenen aufzählbaren Sammlung von Zeichenketten in die Datei, jede Zeichenkette in einer neuen Zeile, unter Verwendung der angegebenen Kodierung. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Erstellt eine neue Textdatei oder überschreibt die bestehende und schreibt alle Zeichenketten aus dem angegebenen Array von Zeichenketten in die Datei, jede Zeichenkette in einer neuen Zeile, unter Verwendung der angegebenen Kodierung. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Erstellt eine neue Textdatei oder überschreibt die bestehende und schreibt den Inhalt der angegebenen Zeichenkette in die Datei unter Verwendung der angegebenen Kodierung. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Standardwert der Anzahl von Bytes, die beim Lesen aus und Schreiben in eine Datei gepuffert werden. |

## Siehe auch

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)