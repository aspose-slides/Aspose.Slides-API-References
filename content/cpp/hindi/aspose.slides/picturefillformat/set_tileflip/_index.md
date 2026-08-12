---
title: set_TileFlip()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "टेक्सचर टाइल को उसकी क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर घुमाता है। Slides::TileFlip लिखें।"
type: docs
weight: 417
url: /hi/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) विधि

टेक्सचर टाइल को उसकी क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर घुमाता है। लिखें [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## टिप्पणी

डिफ़ॉल्ट [TileFlip::NoFlip](../../tileflip/) है। 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// शैप का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर टाइल को उसके लम्बवत अक्ष के चारों ओर घुमाता है।
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## देखें

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)