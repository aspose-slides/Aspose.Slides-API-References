---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει υπερσύνδεσμο μακροεντολής κατά κλικ.
type: docs
weight: 79
url: /el/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) method


Ορίζει υπερσύνδεσμο μακροεντολής κατά κλικ.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Όνομα της μακροεντολής |

### Τιμή Επιστροφής

[Hyperlink](../../hyperlink/) αντικείμενο [IHyperlink](../../ihyperlink/)
## Σχόλια



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IHyperlink](../../ihyperlink/)
* Κλάση [String](../../../system/string/)
* Κλάση [HyperlinkManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)