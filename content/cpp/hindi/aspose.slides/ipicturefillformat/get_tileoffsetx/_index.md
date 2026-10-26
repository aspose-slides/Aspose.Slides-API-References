---
title: get_TileOffsetX()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर का क्षैतिज ऑफ़सेट आकार की उत्पत्ति से बिंदुओं में लौटाता है। एक सकारात्मक मान टेक्सचर को दाएँ की ओर ले जाता है, जबकि एक नकारात्मक मान इसे बाएँ की ओर ले जाता है। पढ़ें float.
type: docs
weight: 274
url: /hi/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() मेथड


टेक्सचर का क्षैतिज ऑफ़सेट आकार की उत्पत्ति से बिंदुओं में देता है। एक सकारात्मक मान टेक्सचर को दाईं ओर ले जाता है, जबकि एक नकारात्मक मान इसे बाईं ओर ले जाता है। पढ़ें **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// शेप का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का क्षैतिज ऑफसेट 20 पॉइंट्स पर सेट करता है
pictureFillFormat->set_TileOffsetX(20.0f);
```

## संबंधित देखें

* क्लास [IPictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)