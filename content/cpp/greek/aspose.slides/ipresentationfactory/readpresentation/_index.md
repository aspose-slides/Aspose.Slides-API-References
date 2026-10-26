---
title: ReadPresentation()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαβάζει μια υπάρχουσα παρουσίαση από πίνακα
type: docs
weight: 27
url: /el/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) μέθοδος

Διαβάζει μια υφιστάμενη παρουσίαση από τον πίνακα

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Πίνακας προς ανάγνωση |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) μέθοδος

Διαβάζει μια υφιστάμενη παρουσίαση από τον πίνακα με επιπρόσθετες επιλογές φόρτωσης

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Πίνακας προς ανάγνωση |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Επιλογές φόρτωσης |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) μέθοδος

Διαβάζει μια υφιστάμενη παρουσίαση από ροή

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή εισόδου προς ανάγνωση |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) μέθοδος

Διαβάζει μια υφιστάμενη παρουσίαση από ροή με επιπρόσθετες επιλογές φόρτωσης

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή εισόδου προς ανάγνωση |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Επιλογές φόρτωσης |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## IPresentationFactory::ReadPresentation(System::String) μέθοδος

Διαβάζει μια υφιστάμενη παρουσίαση από αρχείο

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Όνομα αρχείου |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) μέθοδος

Διαβάζει μια υφιστάμενη παρουσίαση από ροή με επιπρόσθετες επιλογές φόρτωσης

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Όνομα αρχείου |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Επιλογές φόρτωσης |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IPresentation](../../ipresentation/)
* Κλάση [IPresentationFactory](../)
* Κλάση [ILoadOptions](../../iloadoptions/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)