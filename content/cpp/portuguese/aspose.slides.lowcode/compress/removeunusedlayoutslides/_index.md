---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides para C++ Referência da API
description: Realiza a compressão da Apresentação removendo slides de layout não utilizados.
type: docs
weight: 14
url: /pt/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) método

Realiza a compressão do [Presentation](../../../aspose.slides/presentation/) removendo slides de layout não utilizados.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A instância da apresentação |
## Observações




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)