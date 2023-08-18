---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides for C++ API Reference
description: Set external hyperlink on click.
type: docs
weight: 1
url: /aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) method


Set external hyperlink on click.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Remarks



The following sample code shows how to add Text Box with [Hyperlink](../../hyperlink/). 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Gets the first slide in the presentation
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Adds an AutoShape object with type set as Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Accesses the ITextFrame property associated with the AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Adds some text to the frame
portion->set_Text(u"Aspose.Slides");

// Sets the Hyperlink for the portion text
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Saves the PPTX Presentation
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHyperlink](../../ihyperlink/)
* Class [String](../../../system/string/)
* Class [HyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)