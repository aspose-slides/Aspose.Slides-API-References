---
title: GetLinesCount()
second_title: Aspose.Slides for C++ API 參考
description: 取得段落中的行數。
type: docs
weight: 118
url: /zh-hant/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() 方法

取得段落中的行數。

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```

### 傳回值

段落的行數
## 備註

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## 另見

* 類別 [Paragraph](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)