---
title: Presentation()
second_title: Referência da API Aspose.Slides para C++
description: Este construtor cria uma nova apresentação do zero. A apresentação criada tem um slide vazio.
type: docs
weight: 417
url: /pt/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() construtor


Este construtor cria uma nova apresentação do zero. A apresentação criada tem um slide vazio.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) construtor


Este construtor cria uma nova apresentação do zero. A apresentação criada tem um slide vazio.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opções de carregamento adicionais. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) construtor


Este construtor é o mecanismo principal para ler um [Presentation](../) existente.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de entrada. |
## Observações




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) construtor


Este construtor é o mecanismo principal para ler um [Presentation](../) existente.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de entrada. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opções de carregamento adicionais. |

## Presentation::Presentation(System::String) construtor


Este construtor obtém um caminho de arquivo fonte a partir do qual o conteúdo do [Presentation](../) é lido.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Arquivo de entrada. |
## Observações




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) construtor


Este construtor obtém um caminho de arquivo fonte a partir do qual o conteúdo do [Presentation](../) é lido.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Arquivo de entrada. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Opções de carregamento adicionais. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../)
* Classe [LoadOptions](../../loadoptions/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)