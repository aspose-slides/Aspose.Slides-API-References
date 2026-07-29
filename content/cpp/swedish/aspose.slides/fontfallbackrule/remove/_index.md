---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den första förekomsten av ett specifikt FallBack-typsnitt från listan.
type: docs
weight: 118
url: /sv/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) metod


Tar bort den första förekomsten av ett specifikt FallBack-typsnitt från listan.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Typsnittets namn att ta bort från listan. |
## Anmärkningar



```cpp
// Skapa en regel som innehåller en lista med teckensnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Ta bort Tahoma från listan.
newRule->Remove(u"Tahoma");
```


## Se även

* Klass [String](../../../system/string/)
* Klass [FontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)