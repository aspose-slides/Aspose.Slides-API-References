---
title: get_TileScaleY()
second_title: Aspose.Slides for C++ API संदर्भ
description: टेक्सचर फ़िल के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में लौटाता है। पढ़ें float.
type: docs
weight: 352
url: /hi/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() विधि


टेक्सचर फ़िल के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में लौटाता है। पढ़ें **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार का पिक्चर फिल फॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फिल मोड को Tile पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर के लिए ऊर्ध्वाधर स्केल को 120 प्रतिशत पर सेट करता है
pictureFillFormat->set_TileScaleY(120.0f);
```

## देखें

* क्लास [IPictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)