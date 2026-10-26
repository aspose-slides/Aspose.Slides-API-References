---
title: WriteAsSvg()
second_title: Αναφορά API Aspose.Slides για C++
description: Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.
type: docs
weight: 157
url: /el/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) μέθοδος


Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή προορισμού |
## Παρατηρήσεις



Το παρακάτω παράδειγμα κώδικα δείχνει πώς να μετατρέψετε την πρώτη διαφάνεια από παρουσίαση PowerPoint σε αρχείο SVG. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Αποθηκεύει την πρώτη διαφάνεια ως αρχείο SVG
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) μέθοδος


Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή προορισμού |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG generation options |
## Παρατηρήσεις



Το παρακάτω παράδειγμα κώδικα δείχνει πώς να μετατρέψετε την πρώτη διαφάνεια από παρουσίαση PowerPoint σε αρχείο SVG με επιλογές. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Αποθηκεύει την πρώτη διαφάνεια ως αρχείο SVG
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [Slide](../)
* Κλάση [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)