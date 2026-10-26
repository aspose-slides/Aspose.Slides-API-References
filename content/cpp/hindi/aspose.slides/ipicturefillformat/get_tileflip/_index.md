---
title: get_TileFlip()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर उलटता है। पढ़ें Slides::TileFlip."
type: docs
weight: 404
url: /hi/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() मेथड


टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर उलटता है। पढ़ें [Slides::TileFlip](../../tileflip/)।

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## टिप्पणियाँ

डिफ़ॉल्ट है [TileFlip::NoFlip](../../tileflip/)। 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकृति का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भराव मोड को टाइल पर सेट करता है
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