---
title: UpdateDocumentProperties()
second_title: Referência da API Aspose.Slides para C++
description: Atualiza as propriedades da apresentação vinculada.
type: docs
weight: 92
url: /pt/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) método

Atualiza as propriedades da apresentação vinculada.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Propriedades do documento [IDocumentProperties](../../idocumentproperties/) |

## Observações

Este exemplo demonstra como chamar o [IPresentationInfo::UpdateDocumentProperties](./) método para atualizar as propriedades do documento retornadas pela chamada do [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) método.
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDocumentProperties](../../idocumentproperties/)
* Classe [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)