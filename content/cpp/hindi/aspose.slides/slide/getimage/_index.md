---
title: GetImage()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: कस्टम स्केलिंग के साथ एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।
type: docs
weight: 144
url: /hi/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) विधि

कस्टम स्केलिंग के साथ एक थम्बनेल इमेज ऑब्जेक्ट लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| scaleX | **float** | x-अक्ष दिशा में इस थम्बनेल को स्केल करने का मान। |
| scaleY | **float** | y-अक्ष दिशा में इस थम्बनेल को स्केल करने का मान। |

### रिटर्न वैल्यू

[IImage](../../iimage/) ऑब्जेक्ट।

## टिप्पणी

निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../../presentation/) से थम्बनेल कैसे बनाएं: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
निम्न उदाहरण दिखाता है कि स्लाइड्स को बिटमैप में कैसे परिवर्तित किया जाए और PNG में छवियों को सहेजा जाए: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// प्रस्तुति में पहली स्लाइड को एक बिटमैप ऑब्जेक्ट में परिवर्तित करता है
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// छवि को PNG फ़ॉर्मेट में सहेजता है
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
निम्न उदाहरण दिखाता है कि PowerPoint PPT/PPTX को JPG में कैसे परिवर्तित किया जाए: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // पूर्ण स्केल छवि बनाएं
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // छवि को JPEG प्रारूप में डिस्क पर सहेजें
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
निम्न उदाहरण दिखाता है कि कस्टम आकार के साथ PowerPoint PPT/PPTX को JPG में कैसे परिवर्तित किया जाए: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// आयाम निर्धारित करें
int32_t desiredX = 1200;
int32_t desiredY = 800;
// X और Y के स्केल किए हुए मान प्राप्त करें
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // पूर्ण स्केल छवि बनाएं
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // छवि को JPEG प्रारूप में डिस्क पर सहेजें
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() विधि

वास्तविक आकार के 20% के साथ एक थम्बनेल इमेज ऑब्जेक्ट लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) विधि

निर्दिष्ट आकार के साथ एक थम्बनेल इमेज ऑब्जेक्ट लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने के लिये छवि का आकार। |

### रिटर्न वैल्यू

इमेज ऑब्जेक्ट।

## टिप्पणी

निम्न उदाहरण दिखाता है कि C# का उपयोग करके कस्टम आकार के साथ स्लाइड्स को छवियों में कैसे परिवर्तित किया जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// प्रस्तुति में पहली स्लाइड को निर्दिष्ट आकार के साथ एक बिटमैप में बदलता है
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// छवि को JPEG प्रारूप में सहेजता है
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) विधि

निर्दिष्ट पैरामीटर के साथ एक थम्बनेल TIFF इमेज ऑब्जेक्ट लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF विकल्प। |

### रिटर्न वैल्यू

इमेज ऑब्जेक्ट।

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) विधि

एक थम्बनेल इमेज ऑब्जेक्ट लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |

### रिटर्न वैल्यू

इमेज ऑब्जेक्ट।

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) विधि

कस्टम स्केलिंग के साथ एक थम्बनेल इमेज ऑब्जेक्ट लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
| scaleX | **float** | x-अक्ष दिशा में इस थम्बनेल को स्केल करने का मान। |
| scaleY | **float** | y-अक्ष दिशा में इस थम्बनेल को स्केल करने का मान। |

### रिटर्न वैल्यू

बिटमैप ऑब्जेक्ट्स।

## टिप्पणी

निम्न उदाहरण दिखाता है कि C# का उपयोग करके नोट्स और टिप्पणियों के साथ स्लाइड्स को [Images](../../images/) में कैसे परिवर्तित किया जाए। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// रेंडरिंग विकल्प बनाएं
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// नोट्स और टिप्पणियों के लेआउट विकल्प बनाएं
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// पृष्ठ पर नोट्स की स्थिति सेट करता है
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// पृष्ठ पर टिप्पणियों की स्थिति सेट करता है
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// टिप्पणी आउटपुट क्षेत्र की चौड़ाई सेट करता है
notesCommentsLayouting->set_CommentsAreaWidth(500);
// टिप्पणियों क्षेत्र का रंग सेट करता है
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// रेंडरिंग के लिए लेआउट विकल्प सेट करें
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// प्रस्तुति की पहली स्लाइड को IImage ऑब्जेक्ट में बदलता है
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// छवि को GIF फ़ॉर्मेट में सहेजता है
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) विधि

निर्दिष्ट आकार के साथ एक थम्बनेल इमेज ऑब्जेक्ट लौटाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने के लिये छवि का आकार। |

### रिटर्न वैल्यू

इमेज ऑब्जेक्ट।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)