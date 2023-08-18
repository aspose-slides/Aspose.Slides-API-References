---
title: Enclose()
second_title: Aspose.Slides for C++ API Reference
description: Encloses a math element in specified characters such as parenthesis or another characters as framing
type: docs
weight: 170
url: /aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) method


Encloses a math element in specified characters such as parenthesis or another characters as framing

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### Return Value

If *beginningCharacter*  and *endingCharacter*  are null, corresponding properties are assigned values only and no new object is created (returns this instance). Otherwise, returns new math element of type Delimiter which includes specified characters as framing and this instance of [MathDelimiter](../) framed inside.
## Remarks



Example: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)