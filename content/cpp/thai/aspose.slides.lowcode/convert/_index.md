---
title: Convert
second_title: Aspose.Slides สำหรับ API อ้างอิง C++
description: เป็นตัวแทนของกลุ่มเมธอดที่มีวัตถุประสงค์เพื่อแปลง Presentation.
type: docs
weight: 27
url: /th/aspose.slides.lowcode/convert/
---
## Convert คลาส

Represents a group of methods intended to convert [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | แปลง [Presentation](../../aspose.slides/presentation/) โดยใช้ส่วนขยายของเส้นทางออกที่ส่งเข้ามาเพื่อกำหนดรูปแบบการส่งออกที่ต้องการ. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | แปลงการนำเสนอขาเข้าเป็นชุดของภาพรูปแบบ JPEG. 

 If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | แปลงการนำเสนอขาเข้าเป็นชุดของภาพรูปแบบ JPEG. 

 If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | แปลงการนำเสนอขาเข้าเป็นชุดของภาพรูปแบบ JPEG. 

 If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | แปลงการนำเสนอขาเข้าเป็นชุดของภาพรูปแบบ PNG. 

 If the output file name is given as \"myPath/myFilename.png\", the result will be saved as a set of \"myPath/myFilename_N.png\" files, where N is a slide number. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | แปลงการนำเสนอขาเข้าเป็นชุดของภาพรูปแบบ PNG. 

 If the output file name is given as \"myPath/myFilename.png\", the result will be saved as a set of \"myPath/myFilename_N.png\" files, where N is a slide number. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | แปลงการนำเสนอขาเข้าเป็นชุดของภาพรูปแบบ PNG. 

 If the output file name is given as \"myPath/myFilename.png\", the result will be saved as a set of \"myPath/myFilename_N.png\" files, where N is a slide number. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | แปลง [Presentation](../../aspose.slides/presentation/) เป็น SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | แปลงการนำเสนอขาเข้าเป็นชุดของภาพรูปแบบ TIFF. 

 If the output file name is given as \"myPath/myFilename.tiff\", the result will be saved as a set of \"myPath/myFilename_N.tiff\" files, where N is a slide number. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | แปลงการนำเสนอขาเข้าเป็นรูปแบบ TIFF พร้อมตัวเลือกกำหนดเอง. 

 If the output file name is given as \"myPath/myFilename.tiff\" and *multipage*  is **false**, the result will be saved as a set of \"myPath/myFilename_N.tiff\" files, where N is a slide number. Otherwise, if *multipage*  is **true**, the result will be a multi-page \"myPath/myFilename.tiff\" document. |
## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ [Slide](../../aspose.slides/slide/) โดยคาดว่าพาธผลลัพธ์จะถูกส่งกลับ. |
## หมายเหตุ



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::LowCode](../)
* ไลบรารี [Aspose.Slides](../../)