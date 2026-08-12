---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API संदर्भ
description: SVG छवि को EMF फ़ाइल के रूप में सहेजता है।
type: docs
weight: 66
url: /hi/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) मेथड

SVG छवि को EMF फ़ाइल के रूप में सहेजता है।

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | लक्षित स्ट्रीम |

## टिप्पणियाँ

निम्नलिखित उदाहरण दर्शाता है कि SVG छवि को मेटाफाइल में कैसे सहेजा जा सकता है।
```cpp
// नया SVG इमेज बनाता है
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// SVG इमेज को एक मेटाफाइल के रूप में सहेजता है
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
यह नमूना दर्शाता है कि प्रस्तुति छवि संग्रह में SVG छवि को मेटाफाइल के रूप में कैसे जोड़ा जाए।
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// नया SVG इमेज बनाता है
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// SVG इमेज को एक मेटाफाइल के रूप में सहेजता है
svgImage->WriteAsEmf(memStream);
// मेटाफाइल को इमेज संग्रह में जोड़ता है
pres->get_Images()->AddImage(memStream->ToArray());
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [SvgImage](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)