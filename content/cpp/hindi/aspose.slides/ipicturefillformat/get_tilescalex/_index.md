---
title: get_TileScaleX()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर फ़िल के लिए क्षैतिज स्केल को प्रतिशत के रूप में लौटाता है। पढ़ें float.
type: docs
weight: 326
url: /hi/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() विधि


टेक्सचर फ़िल के लिए क्षैतिज स्केल को प्रतिशत में लौटाता है। पढ़ें **float**।

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार के चित्र भराव स्वरूप को प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भराव मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर के लिए क्षैतिज स्केल को 120 प्रतिशत पर सेट करता है
pictureFillFormat->set_TileScaleX(120.0f);
```

## सम्बंधित देखें

* क्लास [IPictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)