---
title: WriteAsEmf()
second_title: Referência da API Aspose.Slides para C++
description: Salva a imagem SVG como um arquivo EMF.
type: docs
weight: 66
url: /pt/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) método


Salva a imagem SVG como um arquivo EMF.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de destino |
## Observações



O exemplo a seguir demonstra como salvar a imagem SVG em um metafile. 
```cpp
// Cria a nova imagem SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Salva a imagem SVG como um metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Esta amostra demonstra como adicionar a imagem SVG como um metafile à coleção de imagens da apresentação. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Cria a nova imagem SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Salva a imagem SVG como um metafile
svgImage->WriteAsEmf(memStream);
// Adiciona o metafile à coleção de imagens
pres->get_Images()->AddImage(memStream->ToArray());
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [SvgImage](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)