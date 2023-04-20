---
title: Delimit()
second_title: Aspose.Slides for C++ API Reference
description: Delimits all child elements with separator character (without the brackets)
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) method


Delimits all child elements with separator character (without the brackets)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | Character used as a separator |

### Return Value

Instance of [IMathDelimiter](../../imathdelimiter/) element
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)