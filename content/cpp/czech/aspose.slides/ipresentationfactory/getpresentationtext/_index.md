---
title: GetPresentationText()
second_title: Aspose.Slides pro C++ API Reference
description: Načte surový text ze snímků
type: docs
weight: 40
url: /cs/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metoda

Načte surový text ze snímků

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Vstupní soubor |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Režim extrakce |

### Return Value

Instanci [PresentationText](../../presentationtext/) obsahující pole SlideText představující surový text snímků

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metoda

Načte surový text ze snímků

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Režim extrakce |

### Return Value

Instanci [PresentationText](../../presentationtext/) obsahující pole SlideText představující surový text snímků

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metoda

Načte surový text ze snímků

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Režim extrakce |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Možnosti načtení |

### Return Value

Instanci [PresentationText](../../presentationtext/) obsahující pole SlideText představující surový text snímků

## Viz také

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IPresentationText](../../ipresentationtext/)
* třída [String](../../../system/string/)
* třída [IPresentationFactory](../)
* třída [Stream](../../../system.io/stream/)
* třída [ILoadOptions](../../iloadoptions/)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)