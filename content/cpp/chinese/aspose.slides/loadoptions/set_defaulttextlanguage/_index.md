---
title: set_DefaultTextLanguage()
second_title: Aspose.Slides for C++ API 参考
description: "设置演示文稿文本的默认语言。写入 System::String."
type: docs
weight: 326
url: /zh/aspose.slides/loadoptions/set_defaulttextlanguage/
---
## LoadOptions::set_DefaultTextLanguage(System::String) 方法


设置演示文稿文本的默认语言。写入 [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultTextLanguage(System::String value) override
```

## 备注


示例： 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DefaultTextLanguage(u"en-US");

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(loadOptions);

// Add new rectangle shape with text
System::SharedPtr<IAutoShape> shp = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
shp->get_TextFrame()->set_Text(u"New Text");

// Check the first portion language
System::SharedPtr<IPortion> portion = shp->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
System::Console::WriteLine(portion->get_PortionFormat()->get_LanguageId());
```

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)