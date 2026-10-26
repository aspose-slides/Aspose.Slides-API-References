---
title: set_TileOffsetX()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर को आकृति की मूल बिंदु से बिंदुओं में क्षैतिज ऑफ़सेट सेट करता है। एक सकारात्मक मान टेक्सचर को दाएँ की ओर ले जाता है, जबकि नकारात्मक मान इसे बाएँ की ओर ले जाता है। लिखें float.
type: docs
weight: 287
url: /hi/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) विधि

टेक्सचर को आकृति की मूल बिंदु से बिंदुओं में क्षैतिज ऑफ़सेट सेट करता है। एक सकारात्मक मान टेक्सचर को दाएँ की ओर ले जाता है, जबकि नकारात्मक मान इसे बाएँ की ओर ले जाता है। लिखें **float**।

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// शेप के पिक्चर फ़िल फॉर्मेट को प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का क्षैतिज ऑफ़सेट 20 पॉइंट्स पर सेट करता है
pictureFillFormat->set_TileOffsetX(20.0f);
```

## संबंधित देखें

* क्लास [IPictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)