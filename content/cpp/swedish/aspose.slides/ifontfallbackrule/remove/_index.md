---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den första förekomsten av ett specifikt FallBack-typsnitt från listan.
type: docs
weight: 79
url: /sv/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) metod

Tar bort den första förekomsten av ett specifikt FallBack-typsnitt från listan.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Typsnittets namn att ta bort från listan. |
## Anmärkningar

```cpp
// Skapa en regel som innehåller en lista med typsnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tar bort Tahoma från listan
newRule->Remove(u"Tahoma");
```

## Se också

* Klass [String](../../../system/string/)
* Klass [IFontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)