---
title: set_TileScaleX()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर फ़िल के लिए क्षैतिज स्केल को प्रतिशत के रूप में सेट करता है। लिखें **float**।
type: docs
weight: 339
url: /hi/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) विधि

टेक्सचर फ़िल के लिए क्षैतिज स्केल को प्रतिशत के रूप में सेट करता है। लिखें **float**।

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकृति का चित्र भराव प्रारूप प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भराव मोड को Tile सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर के क्षैतिज स्केल को 120 प्रतिशत पर सेट करता है
pictureFillFormat->set_TileScaleX(120.0f);
```

## संबंधित देखें

* वर्ग [IPictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)