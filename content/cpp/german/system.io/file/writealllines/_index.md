---
title: WriteAllLines()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue Textdatei oder überschreibt die vorhandene und schreibt alle Zeichenketten aus der angegebenen aufzählbaren Sammlung von Zeichenketten in die Datei, jede Zeichenkette in einer neuen Zeile, unter Verwendung der angegebenen Codierung.
type: docs
weight: 456
url: /de/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) Methode


Erstellt eine neue Textdatei oder überschreibt die vorhandene und schreibt alle Zeichenketten aus der angegebenen aufzählbaren Sammlung von Zeichenketten in die Datei, jede Zeichenkette in einer neuen Zeile, unter Verwendung der angegebenen Codierung.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Die Datei, die erstellt oder überschrieben werden soll |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Eine aufzählbare Sammlung von Zeichenketten |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) Methode


Erstellt eine neue Textdatei oder überschreibt die vorhandene und schreibt alle Zeichenketten aus dem angegebenen Array von Zeichenketten in die Datei, jede Zeichenkette in einer neuen Zeile, unter Verwendung der angegebenen Codierung.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Die Datei, die erstellt oder überschrieben werden soll |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Ein Zeichenketten-Array |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)