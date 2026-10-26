---
title: SetExternalHyperlinkClick()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίστε εξωτερική υπερσύνδεση κατά το κλικ.
type: docs
weight: 1
url: /el/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) μέθοδος

Ορίστε εξωτερική υπερσύνδεση κατά το κλικ.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Παρατηρήσεις

Ο παρακάτω κώδικας δείγματος δείχνει πώς να προσθέσετε Πλαίσιο κειμένου με [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Λαμβάνει την πρώτη διαφάνεια στην παρουσίαση
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Προσθέτει ένα αντικείμενο AutoShape με τύπο ορισμένο ως Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Πρόσβαση στην ιδιότητα ITextFrame που σχετίζεται με το AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Προσθέτει κείμενο στο πλαίσιο
portion->set_Text(u"Aspose.Slides");

// Ορίζει το Hyperlink για το κείμενο του τμήματος
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Αποθηκεύει την παρουσίαση PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IHyperlink](../../ihyperlink/)
* Κλάση [String](../../../system/string/)
* Κλάση [HyperlinkManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)