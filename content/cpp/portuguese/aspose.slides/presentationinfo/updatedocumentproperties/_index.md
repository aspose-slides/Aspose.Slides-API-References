---
title: UpdateDocumentProperties()
second_title: Referência da API Aspose.Slides para C++
description: Atualiza as propriedades da apresentação vinculada.
type: docs
weight: 92
url: /pt/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) método

Atualiza as propriedades da apresentação vinculada.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Observações

Este exemplo mostra como chamar o método [PresentationInfo::UpdateDocumentProperties](./) para atualizar as propriedades do documento retornadas pela chamada do método [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/).
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDocumentProperties](../../idocumentproperties/)
* Classe [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)