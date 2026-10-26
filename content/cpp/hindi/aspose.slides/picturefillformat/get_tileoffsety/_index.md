---
title: get_TileOffsetY()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्सचर को आकार की उत्पत्ति से बिंदुओं में लंबवत ऑफसेट लौटाता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि एक नकारात्मक मान इसे ऊपर ले जाता है। पढ़ें float.
type: docs
weight: 300
url: /hi/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() विधि

टेक्सचर को आकार की उत्पत्ति से बिंदुओं में लंबवत ऑफसेट लौटाता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि एक नकारात्मक मान इसे ऊपर ले जाता है। पढ़ें **float**।

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// आकार के चित्र फ़िल फ़ॉर्मेट को प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र फ़िल मोड को टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का लंबवत ऑफसेट -50 पॉइंट्स पर सेट करता है
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## देखें

* क्लास [PictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)