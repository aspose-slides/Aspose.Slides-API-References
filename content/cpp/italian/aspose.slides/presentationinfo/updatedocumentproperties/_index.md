---
title: UpdateDocumentProperties()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiorna le proprietà della presentazione collegata.
type: docs
weight: 92
url: /it/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metodo

Aggiorna le proprietà della presentazione collegata.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Osservazioni

Questo esempio mostra come chiamare il metodo [PresentationInfo::UpdateDocumentProperties](./) per aggiornare le proprietà del documento restituite dalla chiamata del metodo [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDocumentProperties](../../idocumentproperties/)
* Classe [PresentationInfo](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)