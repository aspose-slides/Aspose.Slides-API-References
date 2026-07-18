---
title: GetPresentationText()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες
type: docs
weight: 40
url: /el/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) μέθοδος


Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Αρχείο εισόδου |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Λειτουργία εξαγωγής |

### Τιμή επιστροφής

Το παράδειγμα του [PresentationText](../../presentationtext/) που περιέχει τον πίνακα SlideText που αντιπροσωπεύει το ακατέργαστο κείμενο των διαφανειών

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) μέθοδος


Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή εισόδου |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Λειτουργία εξαγωγής |

### Τιμή επιστροφής

Το παράδειγμα του [PresentationText](../../presentationtext/) που περιέχει τον πίνακα SlideText που αντιπροσωπεύει το ακατέργαστο κείμενο των διαφανειών

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) μέθοδος


Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή εισόδου |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Λειτουργία εξαγωγής |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Επιλογές φόρτωσης |

### Τιμή επιστροφής

Το παράδειγμα του [PresentationText](../../presentationtext/) που περιέχει τον πίνακα SlideText που αντιπροσωπεύει το ακατέργαστο κείμενο των διαφανειών

## Δείτε επίσης

* Απαριθμός [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPresentationText](../../ipresentationtext/)
* Κλάση [String](../../../system/string/)
* Κλάση [IPresentationFactory](../)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [ILoadOptions](../../iloadoptions/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)