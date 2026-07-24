---
title: KeyValuePair
second_title: Aspose.Slides für C++ API-Referenz
description: "Paar aus Schlüssel und Wert. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 378
url: /de/system.collections.generic/keyvaluepair/
---
## KeyValuePair Klasse

Paar aus Schlüssel und Wert. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Gibt den Schlüssel zurück. |
| const TValue\& [get_Value](./get_value/)() const | Gibt den Wert zurück. |
| int [GetHashCode](./gethashcode/)() const | Berechnet den Hash des Schlüssel-Wert-Paares, indem die Hashes von Schlüssel und Wert per XOR kombiniert werden. |
| **bool** [IsNull](./isnull/)() const | Gibt immer false zurück. |
| [KeyValuePair](./keyvaluepair/)() | Null-Initialisierer für Schlüssel-Wert-Paar. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Typkonversionskonstruktor. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Patch für von IComparer<KeyValuePair<TKey, TValue>> abgeleitete Klassen, vergleicht nichts. |
| [String](../../system/string/) [ToString](./tostring/)() const | Konvertiert das Schlüssel-Wert-Paar in einen String. |

## Siehe auch

* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)