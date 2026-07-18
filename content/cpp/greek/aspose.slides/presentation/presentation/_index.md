---
title: Presentation()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από το μηδέν. Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια.
type: docs
weight: 417
url: /el/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() Κατασκευαστής


Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από το μηδέν. Η δημιουργημένη παρουσίαση έχει μια κενή διαφάνεια.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) Κατασκευαστής


Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από το μηδέν. Η δημιουργημένη παρουσίαση έχει μια κενή διαφάνεια.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Πρόσθετες επιλογές φόρτωσης. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) Κατασκευαστής


Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση ενός υπάρχοντος [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή εισόδου. |
## Παρατηρήσεις




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) Κατασκευαστής


Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση ενός υπάρχοντος [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή εισόδου. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Πρόσθετες επιλογές φόρτωσης. |

## Presentation::Presentation(System::String) Κατασκευαστής


Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή του αρχείου πηγής από την οποία διαβάζονται τα περιεχόμενα του [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Αρχείο εισόδου. |
## Παρατηρήσεις




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) Κατασκευαστής


Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή του αρχείου πηγής από την οποία διαβάζονται τα περιεχόμενα του [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Αρχείο εισόδου. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Πρόσθετες επιλογές φόρτωσης. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Presentation](../)
* Κλάση [LoadOptions](../../loadoptions/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)