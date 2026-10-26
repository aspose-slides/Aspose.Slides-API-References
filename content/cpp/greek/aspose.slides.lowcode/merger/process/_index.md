---
title: Process()
second_title: Aspose.Slides για την Αναφορά API C++
description: Συγχωνεύει πολλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.
type: docs
weight: 1
url: /el/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) method


Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ένα σύνολο των ονομάτων των αρχείων παρουσίασης εισόδου. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα του αρχείου εξόδου του προκύπτοντος ενσωματωμένου αρχείου παρουσίασης. |
## Παρατηρήσεις




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) method


Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ένα σύνολο των ονομάτων των αρχείων παρουσίασης εισόδου. |
| outputFileName | [System::String](../../../system/string/) | Το όνομα του αρχείου εξόδου του προκύπτοντος ενσωματωμένου αρχείου παρουσίασης. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Οι πρόσθετες επιλογές που ορίζουν πώς θα αποθηκευτεί η συγχωνευμένη παρουσίαση. |
## Παρατηρήσεις




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) method


Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ένα σύνολο των ονομάτων των αρχείων παρουσίασης εισόδου. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Η ροή εξόδου. |
## Παρατηρήσεις 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) method


Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint του ίδιου μορφότυπου σε ένα ενιαίο αρχείο παρουσίασης.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Ένα σύνολο των ονομάτων των αρχείων παρουσίασης εισόδου. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Η ροή εξόδου. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Οι πρόσθετες επιλογές που ορίζουν πώς θα αποθηκευτεί η συγχωνευμένη παρουσίαση. |
## Παρατηρήσεις 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Merger](../)
* Κλάση [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)