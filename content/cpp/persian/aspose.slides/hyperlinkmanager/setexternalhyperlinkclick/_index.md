---
title: SetExternalHyperlinkClick()
second_title: مرجع API Aspose.Slides برای C++
description: تنظیم پیوند خارجی هنگام کلیک.
type: docs
weight: 1
url: /fa/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) متد

Set external hyperlink on click.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |

## توضیحات

The following sample code shows how to add Text Box with [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// دریافت اولین اسلاید در ارائه
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// افزودن یک شیء AutoShape با نوع تنظیم‌شده به مستطیل
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// دسترسی به ویژگی ITextFrame مرتبط با AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// افزودن متنی به قاب
portion->set_Text(u"Aspose.Slides");

// تنظیم Hyperlink برای متن بخش
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// ذخیرهٔ ارائه PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## See Also

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IHyperlink](../../ihyperlink/)
* کلاس [String](../../../system/string/)
* کلاس [HyperlinkManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)