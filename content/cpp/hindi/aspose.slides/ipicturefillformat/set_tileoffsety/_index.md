---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API संदर्भ
description: टेक्सचर को आकार के मूल बिंदु से पॉइंट्स में ऊर्ध्वाधर ऑफ़सेट सेट करता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि एक नकारात्मक मान इसे ऊपर ले जाता है। लिखें float.
type: docs
weight: 313
url: /hi/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) विधि


टेक्सचर को आकार के मूल बिंदु से पॉइंट्स में ऊर्ध्वाधर ऑफ़सेट सेट करता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि एक नकारात्मक मान इसे ऊपर ले जाता है। लिखें **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का ऊर्ध्वाधर ऑफ़सेट -50 पॉइंट्स पर सेट करता है
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## देखें

* क्लास [IPictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)