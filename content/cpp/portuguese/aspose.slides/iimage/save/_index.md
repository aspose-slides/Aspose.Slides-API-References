---
title: Save()
second_title: Referência de API do Aspose.Slides para C++
description: Salva a imagem em um arquivo.
type: docs
weight: 40
url: /pt/aspose.slides/iimage/save/
---
## IImage::Save(System::String) método


Salva a imagem em um arquivo.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | O caminho para o arquivo onde a imagem será salva. |

## IImage::Save(System::String, ImageFormat) método


Salva a imagem em um arquivo no formato especificado.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | O caminho para o arquivo onde a imagem será salva. |
| format | [ImageFormat](../../imageformat/) | O formato da imagem. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) método


Salva a imagem em um fluxo no formato especificado.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | O fluxo onde a imagem será salva. |
| format | [ImageFormat](../../imageformat/) | O formato da imagem. |

## IImage::Save(System::String, ImageFormat, int32_t) método


Salva a imagem em um arquivo no formato especificado e com qualidade.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | O caminho para o arquivo onde a imagem será salva. |
| format | [ImageFormat](../../imageformat/) | O formato da imagem. |
| quality | **int32_t** | A qualidade da imagem salva (0 a 100). 

 Este parâmetro só afeta a gravação em [ImageFormat::Jpeg](../../imageformat/); para todos os outros formatos, ele é ignorado. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) método


Salva a imagem em um fluxo no formato especificado e com qualidade.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | O fluxo onde a imagem será salva. |
| format | [ImageFormat](../../imageformat/) | O formato da imagem. |
| quality | **int32_t** | A qualidade da imagem salva (0 a 100). 

 Este parâmetro só afeta a gravação em [ImageFormat::Jpeg](../../imageformat/); para todos os outros formatos, ele é ignorado. |

## Veja Também

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IImage](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)