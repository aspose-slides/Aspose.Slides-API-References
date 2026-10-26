---
title: WriteAsSvg()
second_title: Referência da API Aspose.Slides para C++
description: Salva o conteúdo do slide como um arquivo SVG.
type: docs
weight: 157
url: /pt/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) método


Salva o conteúdo do slide como um arquivo SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de destino |
## Observações



O exemplo de código a seguir demonstra como converter o primeiro slide de uma apresentação PowerPoint em um arquivo SVG. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Salva o primeiro slide como um arquivo SVG
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) método


Salva o conteúdo do slide como um arquivo SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de destino |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | opções de geração SVG |
## Observações



O exemplo de código a seguir demonstra como converter o primeiro slide de uma apresentação PowerPoint em um arquivo SVG com opções. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Salva o primeiro slide como um arquivo SVG
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [Slide](../)
* Classe [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)