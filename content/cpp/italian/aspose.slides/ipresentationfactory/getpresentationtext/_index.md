---
title: GetPresentationText()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera il testo grezzo dalle diapositive
type: docs
weight: 40
url: /it/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metodo

Recupera il testo grezzo dalle diapositive

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File di input |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modalità di estrazione |

### Valore di ritorno

L'istanza di [PresentationText](../../presentationtext/) contenente l'array SlideText che rappresenta il testo grezzo delle diapositive

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metodo

Recupera il testo grezzo dalle diapositive

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso di input |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modalità di estrazione |

### Valore di ritorno

L'istanza di [PresentationText](../../presentationtext/) contenente l'array SlideText che rappresenta il testo grezzo delle diapositive

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metodo

Recupera il testo grezzo dalle diapositive

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso di input |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modalità di estrazione |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

L'istanza di [PresentationText](../../presentationtext/) contenente l'array SlideText che rappresenta il testo grezzo delle diapositive

## Vedi anche

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationText](../../ipresentationtext/)
* Classe [String](../../../system/string/)
* Classe [IPresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [ILoadOptions](../../iloadoptions/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)