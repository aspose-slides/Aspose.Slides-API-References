---
title: GetLinesCount()
second_title: Aspose.Slides C++ API 参考
description: 获取段落中的行数。
type: docs
weight: 105
url: /zh/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() 方法


获取段落中的行数。

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```


### 返回值

段落中的行数
## 备注


示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## 另见

* 类 [IParagraph](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)