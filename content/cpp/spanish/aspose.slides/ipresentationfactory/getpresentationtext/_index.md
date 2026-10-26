---
title: GetPresentationText()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera el texto sin formato de las diapositivas
type: docs
weight: 40
url: /es/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) método


Recupera el texto sin formato de las diapositivas

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Archivo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extracción |

### Valor devuelto

La instancia de [PresentationText](../../presentationtext/) que contiene la matriz SlideText que representa el texto sin formato de las diapositivas

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) método


Recupera el texto sin formato de las diapositivas

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Secuencia de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extracción |

### Valor devuelto

La instancia de [PresentationText](../../presentationtext/) que contiene la matriz SlideText que representa el texto sin formato de las diapositivas

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) método


Recupera el texto sin formato de las diapositivas

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Secuencia de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extracción |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opciones de carga |

### Valor devuelto

La instancia de [PresentationText](../../presentationtext/) que contiene la matriz SlideText que representa el texto sin formato de las diapositivas

## Ver también

* Enumeración [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IPresentationText](../../ipresentationtext/)
* Clase [String](../../../system/string/)
* Clase [IPresentationFactory](../)
* Clase [Stream](../../../system.io/stream/)
* Clase [ILoadOptions](../../iloadoptions/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)