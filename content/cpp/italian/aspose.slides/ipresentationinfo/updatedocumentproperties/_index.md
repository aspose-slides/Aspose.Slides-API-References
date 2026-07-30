---
title: UpdateDocumentProperties()
second_title: Aspose.Slides per C++ API Reference
description: Aggiorna le proprietà della presentazione associata.
type: docs
weight: 92
url: /it/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metodo

Aggiorna le proprietà della presentazione associata.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Proprietà del documento [IDocumentProperties](../../idocumentproperties/) |

## Osservazioni

Questo esempio mostra come chiamare il [IPresentationInfo::UpdateDocumentProperties](./) metodo per aggiornare le proprietà del documento restituite dalla chiamata al [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) metodo.
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
* Classe [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)