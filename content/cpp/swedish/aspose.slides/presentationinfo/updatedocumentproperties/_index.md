---
title: UpdateDocumentProperties()
second_title: Aspose.Slides för C++ API-referens
description: Uppdaterar egenskaper för den bundna presentationen.
type: docs
weight: 92
url: /sv/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metod


Uppdaterar egenskaper för den bundna presentationen.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Anmärkningar


Detta exempel visar hur man anropar [PresentationInfo::UpdateDocumentProperties](./) metod för att uppdatera dokumentegenskaperna som returneras av anropet av [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) metod. 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDocumentProperties](../../idocumentproperties/)
* Klass [PresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)