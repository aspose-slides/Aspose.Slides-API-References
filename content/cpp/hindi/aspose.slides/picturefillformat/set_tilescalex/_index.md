---
title: set_TileScaleX()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर फिल के लिए क्षैतिज स्केल को प्रतिशत के रूप में सेट करता है। float लिखें।
type: docs
weight: 339
url: /hi/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) विधि


टेक्सचर फिल के लिए क्षैतिज स्केल को प्रतिशत के रूप में सेट करता है। **float** लिखें।

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार का पिक्चर फिल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फिल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर के लिए क्षैतिज स्केल को 120 प्रतिशत पर सेट करता है
pictureFillFormat->set_TileScaleX(120.0f);
```

## संबंधित देखें

* क्लास [PictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)