---
title: GetPresentationText()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες
type: docs
weight: 53
url: /el/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) μέθοδος

Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### Τιμή Επιστροφής

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) μέθοδος

Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### Τιμή Επιστροφής

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) μέθοδος

Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Τιμή Επιστροφής

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## Δείτε επίσης

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPresentationText](../../ipresentationtext/)
* Κλάση [String](../../../system/string/)
* Κλάση [PresentationFactory](../)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [ILoadOptions](../../iloadoptions/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)