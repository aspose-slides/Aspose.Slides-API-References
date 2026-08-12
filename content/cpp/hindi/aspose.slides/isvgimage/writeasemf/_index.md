---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API संदर्भ
description: SVG छवि को EMF फ़ाइल के रूप में सहेजता है।
type: docs
weight: 53
url: /hi/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) मेथड

SVG छवि को EMF फ़ाइल के रूप में सहेजता है।

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | लक्षित स्ट्रीम |
## टिप्पणियाँ

The following example demonstrates how to save the SVG image into a metafile. 
```cpp
// नई SVG छवि बनाता है
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// SVG छवि को एक मेटाफाइल के रूप में सहेजता है
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
यह नमूना दर्शाता है कि प्रस्तुति छवि संग्रह में SVG छवि को मेटाफाइल के रूप में कैसे जोड़ें। 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// नई SVG छवि बनाता है
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// SVG छवि को एक मेटाफाइल के रूप में सहेजता है
svgImage->WriteAsEmf(memStream);
// मेटाफाइल को इमेज संग्रह में जोड़ता है
pres->get_Images()->AddImage(memStream->ToArray());
```

## संदर्भ

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [ISvgImage](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)