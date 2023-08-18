---
title: get_Count()
second_title: Aspose.Slides for C++ API Reference
description: Gets the number of elements actually contained in the collection. Read-only int32_t.
type: docs
weight: 1
url: /aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() method


Gets the number of elements actually contained in the collection. Read-only **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## Remarks


Example: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## See Also

* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)