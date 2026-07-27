---
title: GetSensitivityLabels()
second_title: Aspose.Slides para C++ - Referência da API
description: Obtém um array de rótulos de sensibilidade das propriedades de documento personalizadas (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /pt/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() método


Obtém um array de rótulos de sensibilidade das propriedades de documento personalizadas (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Observações


O código a seguir mostra como mover as informações de rótulos de sensibilidade das propriedades de documento personalizadas para a coleção moderna SensitivityLabels: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Obter rótulos de sensibilidade das propriedades de documento personalizadas
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Adicionar rótulo à coleção
    // Aqui você pode adicionar uma verificação da validade das informações do rótulo (o rótulo está disponível, etc.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISensitivityLabel](../../isensitivitylabel/)
* Classe [DocumentProperties](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)