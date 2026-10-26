---
title: SetExternalHyperlinkClick()
second_title: Referensi API Aspose.Slides untuk C++
description: Atur hyperlink eksternal saat diklik.
type: docs
weight: 1
url: /id/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) method


Atur hyperlink eksternal saat diklik.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Remarks



Kode contoh berikut menunjukkan cara menambahkan Text Box dengan [Hyperlink](../../hyperlink/). 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Mendapatkan slide pertama dalam presentasi
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Menambahkan objek AutoShape dengan tipe Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Mengakses properti ITextFrame yang terkait dengan AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Menambahkan beberapa teks ke dalam frame
portion->set_Text(u"Aspose.Slides");

// Mengatur Hyperlink untuk teks bagian
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Menyimpan Presentasi PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHyperlink](../../ihyperlink/)
* Class [String](../../../system/string/)
* Class [HyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)