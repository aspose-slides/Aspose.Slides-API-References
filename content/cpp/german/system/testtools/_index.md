---
title: TestTools
second_title: Aspose.Slides für C++ API Referenz
description: Stellt eine Reihe nützlicher Methoden bereit, die einige grundlegende Eigenschaften verschiedener Typen und Funktionen prüfen.
type: docs
weight: 1925
url: /de/system/testtools/
---
## TestTools Struktur

Stellt eine Reihe nützlicher Methoden bereit, die einige grundlegende Eigenschaften verschiedener Typen und Funktionen prüfen.

```cpp
class TestTools
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Überprüft, ob die Funktion eine Ausnahme beliebigen Typs wirft. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Überprüft, ob die Zeichenkette leer ist. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Überprüft, ob die Sammlung leer ist. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Überprüft, ob ein bestimmter Wert null ist. [Version](../version/) für arithmetische und Aufzählungstypen. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Überprüft, ob ein bestimmter Wert null ist. [Version](../version/) für nicht-arithmetische und nicht-aufzählungsartige Wertetypen. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Überprüft, ob ein bestimmter Wert null ist. [Version](../version/) für nicht-arithmetische Wertetypen. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Überprüft, ob ein bestimmter Wert null ist. [Version](../version/) für Schlüssel-Wert-Paare. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Überprüft, ob die Zeichenkette null ist. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Überprüft, ob die Sammlung null oder leer ist. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Überprüft, ob die Zeichenkette null oder leer ist. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)