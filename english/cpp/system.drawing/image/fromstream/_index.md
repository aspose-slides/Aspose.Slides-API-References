---
title: FromStream()
second_title: Aspose.Slides for C++ API Reference
description: Creates an Image object from the specified stream.
type: docs
weight: 339
url: /cpp/system.drawing/image/fromstream/
---
## Image::FromStream(const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\&, **bool**, **bool**) method


Creates an [Image](../) object from the specified stream.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | A stream that contains image data |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Return Value

A shared pointer to the created [Image](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
