---
title: GetPresentationText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Recupera el texto sin formato de las diapositivas
type: docs
weight: 53
url: /es/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) método

Recupera el texto sin formato de las diapositivas

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Archivo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extracción |

### Valor de retorno

La instancia de [PresentationText](../../presentationtext/) que contiene la matriz SlideText que representa el texto sin formato de las diapositivas

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) método

Recupera el texto sin formato de las diapositivas

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Secuencia de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extracción |

### Valor de retorno

La instancia de [PresentationText](../../presentationtext/) que contiene la matriz SlideText que representa el texto sin formato de las diapositivas

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) método

Recupera el texto sin formato de las diapositivas

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Secuencia de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extracción |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opciones de carga |

### Valor de retorno

La instancia de [PresentationText](../../presentationtext/) que contiene la matriz SlideText que representa el texto sin formato de las diapositivas

## Ver también

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPresentationText](../../ipresentationtext/)
* Clase [String](../../../system/string/)
* Clase [PresentationFactory](../)
* Clase [Stream](../../../system.io/stream/)
* Clase [ILoadOptions](../../iloadoptions/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)