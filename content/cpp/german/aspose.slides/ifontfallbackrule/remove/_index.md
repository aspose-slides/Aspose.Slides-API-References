---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.
type: docs
weight: 79
url: /de/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) Methode


Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Der Name der Schriftart, die aus der Liste entfernt werden soll. |
## Bemerkungen



```cpp
// Erstelle eine Regel, die eine Liste von Schriftarten enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Entfernen von Tahoma aus der Liste
newRule->Remove(u"Tahoma");
```


## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IFontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)