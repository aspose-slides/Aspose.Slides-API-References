---
title: SetExternalHyperlinkClick()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تعيين ارتباط تشعبي خارجي عند النقر.
type: docs
weight: 1
url: /ar/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) طريقة

تعيين ارتباط تشعبي خارجي عند النقر.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## ملاحظات



يعرض المثال التالي كيفية إضافة صندوق نص باستخدام [Hyperlink](../../hyperlink/). 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// يجلب الشريحة الأولى في العرض التقديمي
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// يضيف كائن AutoShape مع تعيين النوع كـ مستطيل
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// يصل إلى خاصية ITextFrame المرتبطة بـ AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// يضيف بعض النص إلى الإطار
portion->set_Text(u"Aspose.Slides");

// يضبط الارتباط التشعبي لنص الجزء
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// يحفظ عرض PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IHyperlink](../../ihyperlink/)
* فئة [String](../../../system/string/)
* فئة [HyperlinkManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)