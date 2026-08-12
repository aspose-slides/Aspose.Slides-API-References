---
title: get_TileScaleY()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर फ़िल के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में लौटाता है। पढ़ें float।
type: docs
weight: 352
url: /hi/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() विधि

टेक्सचर फ़िल के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में लौटाता है। पढ़ें **float**।

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर के लिए ऊर्ध्वाधर स्केल को 120 प्रतिशत पर सेट करता है
pictureFillFormat->set_TileScaleY(120.0f);
```

## देखें भी

* क्लास [PictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)