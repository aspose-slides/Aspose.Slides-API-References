---
title: Enclose()
second_title: Aspose.Slides for C++ API Reference
description: Encloses child elements of this block in specified characters such as parenthesis or another characters as framing
type: docs
weight: 222
url: /aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) method


Encloses child elements of this block in specified characters such as parenthesis or another characters as framing

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
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
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) method


Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
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
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)