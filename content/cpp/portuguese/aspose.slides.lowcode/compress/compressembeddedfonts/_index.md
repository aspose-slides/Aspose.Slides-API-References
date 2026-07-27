---
title: CompressEmbeddedFonts()
second_title: Referência da API Aspose.Slides para C++
description: Realiza a compressão da Presentation removendo caracteres não utilizados das fontes incorporadas.
type: docs
weight: 27
url: /pt/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) método

Realiza a compressão do [Presentation](../../../aspose.slides/presentation/) removendo caracteres não utilizados das fontes incorporadas.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A instância da apresentação |
## Observações




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)