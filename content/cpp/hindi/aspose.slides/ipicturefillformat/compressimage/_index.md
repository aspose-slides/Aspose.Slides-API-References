---
title: CompressImage()
second_title: Aspose.Slides for C++ API संदर्भ
description: चित्र को उसके आकार और निर्दिष्ट रेज़ोल्यूशन के आधार पर आकार घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है।
type: docs
weight: 443
url: /hi/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) method

चित्र को उसके आकार और निर्दिष्ट रेजोल्यूशन के आधार पर आकार घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है।

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | यदि true हो, तो यह मेथड चित्र के क्रॉप किए गए क्षेत्रों को हटा देगा, जिससे उसके आकार में और भी कमी आ सकती है। |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | कम्प्रेशन के लिये लक्षित रेजोल्यूशन, जो [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) enum के मान के रूप में निर्दिष्ट है। |

### Return Value

एक **bool** जो यह दर्शाता है कि चित्र सफलतापूर्वक संकुचित हुआ या नहीं। यह ****true**** लौटाता है।

## Remarks

यह मेथड चित्र के आकार और रेजोल्यूशन को PowerPoint की \"Picture Format -> Compress Pictures\" सुविधा की तरह बदलता है।

यदि चित्र का आकार बदला गया या उसे क्रॉप किया गया हो, अन्यथा ****false****।

निम्न उदाहरण दर्शाता है कि प्रस्तुति में चित्र के आकार को लक्ष्य रेजोल्यूशन सेट करके और क्रॉप किए गए क्षेत्रों को हटाकर **CompressImage** मेथड का उपयोग कैसे किया जाए: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// चित्र को लक्ष्य रेज़ोल्यूशन 150 DPI (वेब रेज़ोल्यूशन) के साथ संकुचित करें और क्रॉप किए गए क्षेत्रों को हटाएँ
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) method

चित्र को उसके आकार और निर्दिष्ट रेजोल्यूशन के आधार पर आकार घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है।

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | यदि true हो, तो यह मेथड चित्र के क्रॉप किए गए क्षेत्रों को हटा देगा, जिससे उसके आकार में और भी कमी आ सकती है। |
| resolution | **float** | DPI में लक्ष्य रेजोल्यूशन। यह मान सकारात्मक होना चाहिए और यह निर्धारित करता है कि चित्र कैसे रिसाइज़ किया जाएगा। |

### Return Value

एक **bool** जो यह दर्शाता है कि चित्र सफलतापूर्वक संकुचित हुआ या नहीं। यह ****true**** लौटाता है।

## Remarks

यह मेथड चित्र के आकार और रेजोल्यूशन को PowerPoint की \"Picture Format -> Compress Pictures\" सुविधा की तरह बदलता है।

यदि चित्र का आकार बदला गया या उसे क्रॉप किया गया हो, अन्यथा ****false****।

निम्न उदाहरण दर्शाता है कि प्रस्तुति में चित्र के आकार को लक्ष्य रेजोल्यूशन सेट करके और क्रॉप किए गए क्षेत्रों को हटाकर **CompressImage** मेथड का उपयोग कैसे किया जाए: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame प्राप्त करता है
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// चित्र को लक्ष्य रेज़ोल्यूशन 150 DPI (वेब रेज़ोल्यूशन) के साथ संकुचित करें और क्रॉप किए गए क्षेत्रों को हटाएँ
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // वेब रेज़ोल्यूशन
```

## See Also

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)