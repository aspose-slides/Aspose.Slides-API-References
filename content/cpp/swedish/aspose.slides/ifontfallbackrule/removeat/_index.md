---
title: RemoveAt()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort FallBack-teckensnittet på det angivna indexet i listan.
type: docs
weight: 92
url: /sv/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) metod


Tar bort FallBack-teckensnittet på det angivna indexet i listan.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för teckensnittet som ska tas bort. |
## Anmärkningar



```cpp
// Skapa en regel som innehåller en lista med teckensnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Tar bort Tahoma från listan
newRule->RemoveAt(2);
```


## Se även

* Klass [IFontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)