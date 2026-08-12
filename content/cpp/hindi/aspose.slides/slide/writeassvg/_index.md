---
title: WriteAsSvg()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड की सामग्री को SVG फ़ाइल के रूप में सहेजता है।
type: docs
weight: 157
url: /hi/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) विधि

स्लाइड की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | लक्ष्य स्ट्रीम |
## टिप्पणियां

निम्नलिखित कोड उदाहरण दर्शाता है कि कैसे PowerPoint प्रस्तुति की पहली स्लाइड को SVG फ़ाइल में परिवर्तित किया जा सकता है। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// पहले स्लाइड को SVG फ़ाइल के रूप में सहेजता है
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) विधि

स्लाइड की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | लक्ष्य स्ट्रीम |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG जनरेशन विकल्प |
## टिप्पणियां

निम्नलिखित कोड उदाहरण दर्शाता है कि कैसे PowerPoint प्रस्तुति की पहली स्लाइड को विकल्पों के साथ SVG फ़ाइल में परिवर्तित किया जा सकता है। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// पहले स्लाइड को SVG फ़ाइल के रूप में सहेजता है
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [Slide](../)
* क्लास [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)