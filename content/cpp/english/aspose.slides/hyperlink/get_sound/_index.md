---
title: get_Sound()
second_title: Aspose.Slides for C++ API Reference
description: Represents the playing sound of the hyperlink. Read IAudio.
type: docs
weight: 274
url: /aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() method


Represents the playing sound of the hyperlink. Read [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first shape hyperlink
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extract the hyperlink sound in byte array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [Hyperlink](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)