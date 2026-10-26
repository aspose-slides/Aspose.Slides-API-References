---
title: WriteAsEmf()
second_title: Referência da API Aspose.Slides para C++
description: Salva a imagem SVG como um arquivo EMF.
type: docs
weight: 53
url: /pt/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) método

Salva a imagem SVG como um arquivo EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de destino |
## Observações

O exemplo a seguir demonstra como salvar a imagem SVG em um metafile.
```cpp
// Cria a nova imagem SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Salva a imagem SVG como um metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Este exemplo demonstra como adicionar a imagem SVG como um metafile à coleção de imagens da apresentação.
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
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)