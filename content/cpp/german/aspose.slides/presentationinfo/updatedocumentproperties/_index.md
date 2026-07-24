---
title: UpdateDocumentProperties()
second_title: Aspose.Slides für C++ API Referenz
description: Aktualisiert die Eigenschaften der gebundenen Präsentation.
type: docs
weight: 92
url: /de/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) Methode

Aktualisiert die Eigenschaften der gebundenen Präsentation.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Hinweise

Dieses Beispiel zeigt, wie man die [PresentationInfo::UpdateDocumentProperties](./) Methode aufruft, um die Dokumenteigenschaften zu aktualisieren, die durch den Aufruf der [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) Methode zurückgegeben werden.
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDocumentProperties](../../idocumentproperties/)
* Klasse [PresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)