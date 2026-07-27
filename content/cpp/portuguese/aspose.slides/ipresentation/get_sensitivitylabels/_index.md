---
title: get_SensitivityLabels()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna a coleção de rótulos de sensibilidade aplicados ao documento de apresentação. Somente leitura ISensitivityLabelCollection.
type: docs
weight: 391
url: /pt/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() método

Retorna a coleção de rótulos de sensibilidade aplicados ao documento de apresentação. Somente leitura [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## Observações

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Imprime os rótulos aplicados
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Adiciona o novo rótulo
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Obtém o Id do rótulo de sensibilidade da política
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Obtém o identificador do site Azure AD da política
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Classe [IPresentation](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)