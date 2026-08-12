---
title: GetLinesCount()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: पैराग्राफ में पंक्तियों की संख्या प्राप्त करें।
type: docs
weight: 118
url: /hi/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() विधि

एक पैराग्राफ में पंक्तियों की संख्या प्राप्त करें।

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```

### वापसी मान

पैराग्राफ में पंक्तियों की गिनती
## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## संबंधित देखें

* क्लास [Paragraph](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)