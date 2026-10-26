---
title: set_TileScaleY()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर फ़िल के लिए लंबवत स्केल को प्रतिशत के रूप में सेट करता है। लिखें float.
type: docs
weight: 365
url: /hi/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) विधि


टेक्सचर फिल के लिए लंबवत स्केल को प्रतिशत के रूप में सेट करता है। लिखें **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// शेप की पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर के लिए लंबवत स्केल को 120 प्रतिशत पर सेट करता है
pictureFillFormat->set_TileScaleY(120.0f);
```

## देखें भी

* क्लास [IPictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)