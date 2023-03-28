---
title: set_Sound()
second_title: Aspose.Slides for C++ API Reference
description: Represents the playing sound of the hyperlink. Write IAudio.
type: docs
weight: 287
url: /cpp/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound([System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\>) method


Represents the playing sound of the hyperlink. Write [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
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
