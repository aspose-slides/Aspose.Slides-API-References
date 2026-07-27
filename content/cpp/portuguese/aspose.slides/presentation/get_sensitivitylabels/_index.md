---
title: get_SensitivityLabels()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. Somente leitura ISensitivityLabelCollection.
type: docs
weight: 378
url: /pt/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() método


Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. Somente leitura [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
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
// Get the sensitivity label Id from the policy
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Get the Azure AD site identifier from the policy
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Classe [Presentation](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)