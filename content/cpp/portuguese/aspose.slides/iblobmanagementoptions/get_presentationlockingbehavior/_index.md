---
title: get_PresentationLockingBehavior()
second_title: Referência da API Aspose.Slides para C++
description: "Esta propriedade define se uma instância da classe Presentation pode ser proprietária da origem — arquivo ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a origem. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a origem (fluxo ou arquivo) não pode ser alterada durante a vida útil da instância de Presentation. Este é um exemplo:"
type: docs
weight: 1
url: /pt/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() método

Esta propriedade define se uma instância da classe [Presentation](../../presentation/) pode ser proprietária da fonte — arquivo ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) não pode ser alterada durante a vida útil da instância de [Presentation](../../presentation/). Este é um exemplo:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Observações

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException será lançada porque pres.pptx está bloqueado por toda a vida da Presentation
    // File::Delete(u"pres.pptx");
}
// após o objeto Presentation ser destruído, o arquivo é desbloqueado e pode ser excluído
IO::File::Delete(u"pres.pptx");
```

## Veja Também

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Classe [IBlobManagementOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)