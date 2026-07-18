---
title: ReadPresentation()
second_title: Aspose.Slides για Αναφορά API C++
description: Διαβάζει μια υπάρχουσα παρουσίαση από πίνακα
type: docs
weight: 40
url: /el/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) μέθοδος

Διαβάζει μια υπάρχουσα παρουσίαση από πίνακα

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Πίνακας για ανάγνωση |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) μέθοδος

Διαβάζει μια υπάρχουσα παρουσίαση από πίνακα με πρόσθετες επιλογές φόρτωσης

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Πίνακας για ανάγνωση |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Επιλογές φόρτωσης |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) μέθοδος

Διαβάζει μια υπάρχουσα παρουσίαση από ροή

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Εισερχόμενη ροή για ανάγνωση |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) μέθοδος

Διαβάζει μια υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Εισερχόμενη ροή για ανάγνωση |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Επιλογές φόρτωσης |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## PresentationFactory::ReadPresentation(System::String) μέθοδος

Διαβάζει μια υπάρχουσα παρουσίαση από αρχείο

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Όνομα αρχείου |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) μέθοδος

Διαβάζει μια υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Όνομα αρχείου |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Επιλογές φόρτωσης |

### Τιμή Επιστροφής

Παρουσίαση που διαβάστηκε

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [PresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)