---
title: get_Count()
second_title: Aspose.Slides for C++ API Reference
description: Gets the number of child math elements actually contained in the collection. Read-only int32_t.
type: docs
weight: 1
url: /aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() method


Gets the number of child math elements actually contained in the collection. Read-only **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## Remarks


Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## See Also

* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)