---
title: set_DefaultTextLanguage()
second_title: مرجع API Aspose.Slides للغة C++
description: "يضبط اللغة الافتراضية لنص العرض التقديمي. اكتب System::String."
type: docs
weight: 326
url: /ar/aspose.slides/iloadoptions/set_defaulttextlanguage/
---
## ILoadOptions::set_DefaultTextLanguage(System::String) طريقة

يضبط اللغة الافتراضية لنص العرض التقديمي. اكتب [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DefaultTextLanguage(System::String value)=0
```

## ملاحظات


مثال: 
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

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [ILoadOptions](../)
* مساحة الأسماء [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)