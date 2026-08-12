---
title: set_TileFlip()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर घुमाता है। लिखें Slides::TileFlip."
type: docs
weight: 417
url: /hi/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) विधि


टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के आसपास फिराता है। लिखें [Slides::TileFlip](../../tileflip/)।

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## टिप्पणी


डिफ़ॉल्ट है [TileFlip::NoFlip](../../tileflip/)। 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// शेप के पिक्चर फ़िल फ़ॉर्मेट को प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर टाइल को उसके लंबवत अक्ष के चारों ओर उलटता है।
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## देखें

* एनम [TileFlip](../../tileflip/)
* क्लास [IPictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)