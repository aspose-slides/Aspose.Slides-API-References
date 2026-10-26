---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides για την αναφορά API του C++
description: Ορίστε υπερσύνδεσμο Macro με κλικ.
type: docs
weight: 79
url: /el/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) method


Ορίστε υπερσύνδεσμο Macro με κλικ.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Όνομα του macro |

### Τιμή επιστροφής

[Hyperlink](../../hyperlink/) αντικείμενο [IHyperlink](../../ihyperlink/)
## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IHyperlink](../../ihyperlink/)
* Κλάση [String](../../../system/string/)
* Κλάση [IHyperlinkManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)