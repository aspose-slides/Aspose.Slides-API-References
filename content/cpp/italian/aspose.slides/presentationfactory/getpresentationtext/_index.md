---
title: GetPresentationText()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera il testo grezzo dalle diapositive
type: docs
weight: 53
url: /it/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method

Recupera il testo grezzo dalle diapositive

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File di input |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modalità di estrazione |

### Valore di ritorno

L'istanza di [PresentationText](../../presentationtext/) contenente l'array SlideText che rappresenta il testo grezzo delle diapositive

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method

Recupera il testo grezzo dalle diapositive

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di input |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modalità di estrazione |

### Valore di ritorno

L'istanza di [PresentationText](../../presentationtext/) contenente l'array SlideText che rappresenta il testo grezzo delle diapositive

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method

Recupera il testo grezzo dalle diapositive

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di input |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modalità di estrazione |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opzioni di caricamento |

### Valore di ritorno

L'istanza di [PresentationText](../../presentationtext/) contenente l'array SlideText che rappresenta il testo grezzo delle diapositive

## Vedi anche

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationText](../../ipresentationtext/)
* Classe [String](../../../system/string/)
* Classe [PresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [ILoadOptions](../../iloadoptions/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)