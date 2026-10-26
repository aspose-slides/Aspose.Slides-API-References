---
title: get_TileOffsetY()
second_title: Aspose.Slides for C++ API संदर्भ
description: टेक्सचर को आकार की मूल स्थिति से बिंदुओं में ऊर्ध्वाधर ऑफ़सेट लौटाता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि एक नकारात्मक मान इसे ऊपर ले जाता है। पढ़ें float.
type: docs
weight: 300
url: /hi/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() विधि


टेक्सचर को आकार की मूल स्थिति से बिंदुओं में ऊर्ध्वाधर ऑफ़सेट लौटाता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि एक नकारात्मक मान इसे ऊपर ले जाता है। पढ़ें **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार का पिक्चर फ़िल फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// पिक्चर फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का ऊर्ध्वाधर ऑफ़सेट -50 पॉइंट पर सेट करता है
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## संबंधित देखें

* वर्ग [IPictureFillFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)