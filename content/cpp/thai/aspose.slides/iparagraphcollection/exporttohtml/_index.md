---
title: ExportToHtml()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แปลงพารากราฟที่ระบุเป็น HTML และส่งคืนเป็นอ็อบเจกต์ประเภท String.
type: docs
weight: 105
url: /th/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) เมธอด

แปลงพารากราฟที่ระบุเป็น HTML และส่งคืนเป็นอ็อบเจกต์ประเภท String.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | ดัชนีพารากราฟแรก **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) จำนวน **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | ตัวเลือกการแปลง [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Return Value

HTML ที่สร้างขึ้น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* คลาส [IParagraphCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)