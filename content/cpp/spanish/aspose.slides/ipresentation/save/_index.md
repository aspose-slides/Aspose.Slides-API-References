---
title: Save()
second_title: Referencia de API de Aspose.Slides para C++
description: Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.
type: docs
weight: 404
url: /es/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) método


Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ruta al archivo creado. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) método


Guarda todas las diapositivas de una presentación en un flujo con el formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de salida. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) método


Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ruta al archivo creado. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opciones de formato adicionales. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) método


Guarda todas las diapositivas de una presentación en un flujo con el formato especificado y con opciones adicionales.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de salida. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opciones de formato adicionales. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) método


Guarda diapositivas específicas de una presentación en un archivo con el formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ruta al archivo creado. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) método


Guarda diapositivas específicas de una presentación en un archivo con el formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Ruta al archivo creado. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opciones de formato adicionales. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) método


Guarda diapositivas específicas de una presentación en un flujo con el formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de salida. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) método


Guarda diapositivas específicas de una presentación en un flujo con el formato especificado.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flujo de salida. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato de los datos exportados. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opciones de formato adicionales. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) método


Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan marcado XAML.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Las opciones del formato XAML. |
## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Véase también

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [IPresentation](../)
* Clase [Stream](../../../system.io/stream/)
* Clase [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Clase [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)