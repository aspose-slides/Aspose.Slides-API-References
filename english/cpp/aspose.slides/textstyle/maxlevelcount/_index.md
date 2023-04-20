---
title: MaxLevelCount
second_title: Aspose.Slides for C++ API Reference
description: Maximum count of style levels that can be defined. Use it with GetLevel(int index)
type: docs
weight: 40
url: /cpp/aspose.slides/textstyle/maxlevelcount/
---
## MaxLevelCount field


Maximum count of style levels that can be defined. Use it with GetLevel(int index)

```cpp
static uint8_t Aspose::Slides::TextStyle::MaxLevelCount
```

## Remarks



```cpp
for (int32_t i = 0; i < TextStyle::MaxLevelCount; i++)
{
    auto paragraphFormat = textStyle->GetLevel(i);
    // ...
}
```

## See Also

* Class [TextStyle](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)