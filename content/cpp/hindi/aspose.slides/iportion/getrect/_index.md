---
title: GetRect()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: portion को सीमित करने वाले rect के निर्देशांक प्राप्त करें। rect में portion के सभी पाठ पंक्तियाँ, जिसमें खाली पंक्तियाँ भी शामिल हैं, सम्मिलित हैं।
type: docs
weight: 79
url: /hi/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() विधि


portion को सीमित करने वाले rect के निर्देशांक प्राप्त करें। rect में portion के सभी पाठ पंक्तियों, जिसमें खाली पंक्तियाँ भी शामिल हैं, सम्मिलित हैं।

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### रिटर्न मान

portion को सीमित करने वाला Rectangle [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## टिप्पणियाँ



उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 50.0f, 50.0f, 200.0f, 50.0f);

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Clear();
auto portion0 = System::MakeObject<Portion>(u"Some text");
auto portion1 = System::MakeObject<Portion>(u"GetRect text");

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion0);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion1);

auto rect = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(1)->GetRect();
// ...
```

## संबंधित देखें

* क्लास [RectangleF](../../../system.drawing/rectanglef/)
* क्लास [IPortion](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)