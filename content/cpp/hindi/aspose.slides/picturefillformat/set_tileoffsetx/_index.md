---
title: set_TileOffsetX()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर का क्षैतिज ऑफसेट, आकार की मूल बिंदु से, पॉइंट्स में सेट करता है। एक सकारात्मक मान टेक्सचर को दाएँ ले जाता है, जबकि नकारात्मक मान उसे बाएँ ले जाता है। लिखें float.
type: docs
weight: 287
url: /hi/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) मेथड

टेक्सचर का क्षैतिज ऑफ़सेट, आकार की मूल बिंदु से, पॉइंट्स में सेट करता है। एक सकारात्मक मान टेक्सचर को दाएँ ले जाता है, जबकि नकारात्मक मान उसे बाएँ ले जाता है। लिखें **float**।

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार के चित्र भराव प्रारूप को प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भराव मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का क्षैतिज ऑफसेट 20 पॉइंट्स पर सेट करता है
pictureFillFormat->set_TileOffsetX(20.0f);
```

## संबंधित देखें

* क्लास [PictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)