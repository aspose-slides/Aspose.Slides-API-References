---
title: Delimit()
second_title: Aspose.Slides for C++ API Reference
description: Delimits child elements with separator character (without the brackets)
type: docs
weight: 209
url: /aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) method


Delimits child elements with separator character (without the brackets)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | Separator character |

### Return Value

The math element of type [IMathDelimiter](../../imathdelimiter/)
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)