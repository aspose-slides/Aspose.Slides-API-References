---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API संदर्भ
description: टेक्सचर का लंबवत ऑफसेट को आकार की मूल बिंदु से पॉइंट्स में सेट करता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान इसे ऊपर ले जाता है। float लिखें।
type: docs
weight: 313
url: /hi/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) मेथड


Sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Write **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// शेप का चित्र भरने का फ़ॉर्मेट प्राप्त करता है
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// चित्र भरने का मोड टाइल पर सेट करता है
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// टेक्सचर का लंबवत ऑफसेट -50 पॉइंट्स पर सेट करता है
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## देखें

* क्लास [PictureFillFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)