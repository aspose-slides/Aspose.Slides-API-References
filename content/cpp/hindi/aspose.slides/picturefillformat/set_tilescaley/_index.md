---
title: set_TileScaleY()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर फ़िल के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में सेट करता है। float लिखें।
type: docs
weight: 365
url: /hi/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) विधि

टेक्सचर फ़िल के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में सेट करता है। **float** लिखें।

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the picture fill format of the shape
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Sets the picture fill mode to Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Sets the vertical scale for the texture to 120 percents
pictureFillFormat->set_TileScaleY(120.0f);
```

## संबंधित देखें

* क्लास [PictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)