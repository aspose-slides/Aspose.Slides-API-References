---
title: Delimit()
second_title: Aspose.Slides for C++ API Reference
description: Delimits arguments using the specified delimiter character
type: docs
weight: 144
url: /aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) method


Delimits arguments using the specified delimiter character

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | delimiter character |

### Return Value

This object after applying the delimiter character
## Remarks



Example: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)