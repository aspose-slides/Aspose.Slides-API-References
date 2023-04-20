---
title: Accent()
second_title: Aspose.Slides for C++ API Reference
description: Sets an accent mark (a character on the top of this element)
type: docs
weight: 209
url: /cpp/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) method


Sets an accent mark (a character on the top of this element)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char16_t | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

### Return Value

New instance of type [IMathAccent](../../imathaccent/)
## Remarks



Example: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)