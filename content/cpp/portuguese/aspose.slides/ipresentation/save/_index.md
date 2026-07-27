---
title: Save()
second_title: Referência da API Aspose.Slides para C++
description: Salva todos os slides de uma apresentação em um arquivo com o formato especificado.
type: docs
weight: 404
url: /pt/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) method

Salva todos os slides de uma apresentação em um arquivo com o formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Caminho para o arquivo criado. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) method

Salva todos os slides de uma apresentação em um fluxo no formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de saída. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Caminho para o arquivo criado. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opções adicionais de formato. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de saída. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opções adicionais de formato. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

Salva slides especificados de uma apresentação em um arquivo com o formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Caminho para o arquivo criado. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz com as posições dos slides, começando em 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva slides especificados de uma apresentação em um arquivo com o formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Caminho para o arquivo criado. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz com as posições dos slides, começando em 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opções adicionais de formato. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

Salva slides especificados de uma apresentação em um fluxo no formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de saída. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz com as posições dos slides, começando em 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Salva slides especificados de uma apresentação em um fluxo no formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de saída. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz com as posições dos slides, começando em 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dos dados exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opções adicionais de formato. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method

Salva todos os slides de uma apresentação em um conjunto de arquivos que representam a marcação XAML.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | As opções de formato XAML. |

## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Veja Também

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IPresentation](../)
* Class [Stream](../../../system.io/stream/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)