---
title: GetRect()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Portion को सीमित करने वाले rect के निर्देशांक प्राप्त करें। यह rect Portion में सभी टेक्स्ट लाइनों को शामिल करता है, जिसमें खाली लाइनों भी शामिल हैं।
type: docs
weight: 92
url: /hi/aspose.slides/portion/getrect/
---
## Portion::GetRect() मेथड


Portion को सीमित करने वाले rect के निर्देशांक प्राप्त करें। यह rect Portion में सभी टेक्स्ट लाइनों को शामिल करता है, जिसमें खाली लाइनों भी शामिल हैं।

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## टिप्पणी


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

## देखें

* क्लास [RectangleF](../../../system.drawing/rectanglef/)
* क्लास [Portion](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)