---
title: get_TileFlip()
second_title: Aspose.Slides for C++ API संदर्भ
description: "टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर फ़्लिप करता है। पढ़ें Slides::TileFlip."
type: docs
weight: 404
url: /hi/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() विधि

टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के आसपास फ़्लिप करता है। पढ़ें [Slides::TileFlip](../../tileflip/)।

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## टिप्पणियाँ

डिफ़ॉल्ट है [TileFlip::NoFlip](../../tileflip/)।

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार के चित्र भरने के स्वरूप को प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भरने के मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर टाइल को उसके लंबवत अक्ष के चारों ओर फ़्लिप करता है।
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## देखें

* एनम [TileFlip](../../tileflip/)
* क्लास [PictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)