---
title: RemoveAt()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort FallBack-typsnittet på det angivna indexet i listan.
type: docs
weight: 131
url: /sv/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) metod

Tar bort FallBack-typsnittet på det angivna indexet i listan.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för typsnittet som ska tas bort. |
## Anmärkningar



```cpp
// Skapa en regel som innehåller en lista med typsnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tar bort Tahoma från listan.
newRule->RemoveAt(2);
```


## Se även

* Klass [FontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)