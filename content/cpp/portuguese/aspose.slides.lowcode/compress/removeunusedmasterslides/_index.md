---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides para Referência da API C++
description: Faz a compressão da Presentation removendo slides mestre não utilizados.
type: docs
weight: 1
url: /pt/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) method


Faz a compressão de [Presentation](../../../aspose.slides/presentation/) removendo slides mestre não utilizados.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A instância da apresentação |
## Observações




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)