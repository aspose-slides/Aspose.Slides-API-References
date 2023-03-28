---
title: Enclose()
second_title: Aspose.Slides for C++ API Reference
description: Encloses a math element in parenthesis
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() method


Encloses a math element in parenthesis

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Return Value

The math element of type [IMathDelimiter](../../imathdelimiter/) which includes the parenthesis
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathElement::Enclose(char16_t, char16_t) method


Encloses this element in specified characters such as parenthesis or another characters as framing

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### Return Value

The math element of type [IMathDelimiter](../../imathdelimiter/) which includes specified characters as framing
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
