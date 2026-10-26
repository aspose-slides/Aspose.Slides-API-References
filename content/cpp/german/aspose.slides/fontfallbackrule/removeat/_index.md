---
title: RemoveAt()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt die FallBack-Schriftart am angegebenen Index der Liste.
type: docs
weight: 131
url: /de/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) Methode

Entfernt die FallBack-Schriftart am angegebenen Index der Liste.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index der zu entfernenden Schriftart. |
## Anmerkungen

```cpp
// Erstelle eine Regel, die eine Schriftartenliste enthält.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Entferne Tahoma aus der Liste.
newRule->RemoveAt(2);
```

## Siehe auch

* Klasse [FontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)