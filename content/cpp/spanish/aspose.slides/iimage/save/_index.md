---
title: Save()
second_title: Referencia de API de Aspose.Slides para C++
description: Guarda la imagen en un archivo.
type: docs
weight: 40
url: /es/aspose.slides/iimage/save/
---
## IImage::Save(System::String) método

Guarda la imagen en un archivo.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | La ruta al archivo donde se guardará la imagen. |

## IImage::Save(System::String, ImageFormat) método

Guarda la imagen en un archivo en el formato especificado.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | La ruta al archivo donde se guardará la imagen. |
| format | [ImageFormat](../../imageformat/) | El formato de la imagen. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) método

Guarda la imagen en un flujo en el formato especificado.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El flujo donde se guardará la imagen. |
| format | [ImageFormat](../../imageformat/) | El formato de la imagen. |

## IImage::Save(System::String, ImageFormat, int32_t) método

Guarda la imagen en un archivo en el formato y calidad especificados.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | La ruta al archivo donde se guardará la imagen. |
| format | [ImageFormat](../../imageformat/) | El formato de la imagen. |
| quality | **int32_t** | La calidad de la imagen guardada (0 a 100). 

Este parámetro solo afecta el guardado en [ImageFormat::Jpeg](../../imageformat/); para todos los demás formatos, se ignora. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) método

Guarda la imagen en un flujo en el formato y calidad especificados.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | El flujo donde se guardará la imagen. |
| format | [ImageFormat](../../imageformat/) | El formato de la imagen. |
| quality | **int32_t** | La calidad de la imagen guardada (0 a 100). 

Este parámetro solo afecta el guardado en [ImageFormat::Jpeg](../../imageformat/); para todos los demás formatos, se ignora. |

## Ver también

* Enumeración [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [IImage](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)