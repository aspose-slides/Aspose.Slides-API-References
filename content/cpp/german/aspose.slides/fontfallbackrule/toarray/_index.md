---
title: ToArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Erzeugt und gibt ein Array mit allen FallBack-Schriften für diese Regel zurück.
type: docs
weight: 144
url: /de/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() Methode

Erzeugt und gibt ein Array mit allen FallBack-Schriften für diese Regel zurück.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Rückgabewert

Array von [System::String](../../../system/string/)
## Hinweise



```cpp
// Erstelle eine Regel, die eine Schriftliste enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Alle Schriftartenamen als Array erhalten.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) Methode

Erzeugt und gibt ein Array mit allen FallBack-Schriften aus dem angegebenen Bereich in der Liste zurück.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **int32_t** | Ein Index der ersten hinzuzufügenden Schrift. |
| count | **int32_t** | Eine Anzahl von hinzuzufügenden Schriften. |

### Rückgabewert

Array von [System::String](../../../system/string/)
## Hinweise



```cpp
// Erstelle eine Regel, die eine Liste von Schriftarten enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Erhalte die letzten beiden Schriftartnamen als Array.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)