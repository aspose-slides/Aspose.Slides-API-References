---
title: Enclose()
second_title: Aspose.Slides for C++ API Reference
description: Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character
type: docs
weight: 14
url: /aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) method


Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |
| separatorCharacter | char16_t | Separator character |

### Return Value

The math element of type [IMathDelimiter](../../imathdelimiter/) which includes specified characters as framing and delimiter
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)