---
title: get_TileOffsetX()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर का क्षैतिज ऑफसेट, आकार की उत्पत्ति से पॉइंट्स में, लौटाता है। एक सकारात्मक मान टेक्सचर को दाएँ की ओर ले जाता है, जबकि नकारात्मक मान उसे बाएँ की ओर ले जाता है। float पढ़ें।
type: docs
weight: 274
url: /hi/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() विधि


टेक्सचर का क्षैतिज ऑफसेट, आकार की उत्पत्ति से पॉइंट्स में, लौटाता है। एक सकारात्मक मान टेक्सचर को दाएँ की ओर ले जाता है, जबकि नकारात्मक मान उसे बाएँ की ओर ले जाता है। पढ़ें **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// शेप का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भराव मोड को Tile पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का क्षैतिज ऑफसेट 20 पॉइंट पर सेट करता है
pictureFillFormat->set_TileOffsetX(20.0f);
```

## देखें भी

* क्लास [PictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)