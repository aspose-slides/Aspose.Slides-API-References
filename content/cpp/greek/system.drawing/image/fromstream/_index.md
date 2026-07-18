---
title: FromStream()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα αντικείμενο Image από τη συγκεκριμένη ροή.
type: docs
weight: 339
url: /el/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) method


Δημιουργεί ένα αντικείμενο [Image](../) από τη συγκεκριμένη ροή.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Μια ροή που περιέχει δεδομένα εικόνας |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Return Value

Ένας κοινός δείκτης προς το δημιουργημένο αντικείμενο [Image](../).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Image](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)