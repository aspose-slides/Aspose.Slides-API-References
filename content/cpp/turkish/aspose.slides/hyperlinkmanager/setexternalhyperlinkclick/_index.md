---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides for C++ API Referansı
description: Tıklama sırasında harici bağlantıyı ayarlar.
type: docs
weight: 1
url: /tr/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) yöntemi

Tıklama sırasında harici bağlantıyı ayarlar.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Açıklamalar

Aşağıdaki örnek kod, [Hyperlink](../../hyperlink/) ile Metin Kutusu eklemenin nasıl yapıldığını gösterir.
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Sunumdaki ilk slaytı alır
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Türü Dikdörtgen olarak ayarlanmış bir AutoShape nesnesi ekler
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// AutoShape ile ilişkili ITextFrame özelliğine erişir
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Çerçeveye bazı metinler ekler
portion->set_Text(u"Aspose.Slides");

// Parça metni için Hyperlink ayarlar
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// PPTX Sunumunu kaydeder
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IHyperlink](../../ihyperlink/)
* Sınıf [String](../../../system/string/)
* Sınıf [HyperlinkManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)