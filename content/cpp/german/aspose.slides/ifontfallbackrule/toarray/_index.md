---
title: ToArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt und gibt ein Array mit allen FallBack-Schriften für diese Regel zurück.
type: docs
weight: 105
url: /de/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() Methode

Erstellt und gibt ein Array mit allen FallBack-Schriften für diese Regel zurück.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### Rückgabewert

Array von [System::String](../../../system/string/)
## Hinweise

```cpp
// Erstelle eine Regel, die eine Liste von Schriften enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Alle Schriftnamen als Array erhalten
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) Methode

Erstellt und gibt ein Array mit allen FallBack-Schriften aus dem angegebenen Bereich in der Liste zurück.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
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
// Erstelle eine Regel, die eine Liste von Schriften enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Erhalte die letzten beiden Schriftnamen als Array
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IFontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)