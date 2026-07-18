---
title: AddFromHtml()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.
type: docs
weight: 196
url: /el/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML για προσθήκη. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο επιστροφής κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή επιστροφής

Διαφάνειες που προστέθηκαν.

## SlideCollection::AddFromHtml(System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML για προσθήκη. |

### Τιμή επιστροφής

Διαφάνειες που προστέθηκαν

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο επιστροφής κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή επιστροφής

Διαφάνειες που προστέθηκαν.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή αρχείου HTML. |

### Τιμή επιστροφής

Διαφάνειες που προστέθηκαν

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο επιστροφής κλήσης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή επιστροφής

Διαφάνειες που προστέθηκαν.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή αρχείου HTML. |

### Τιμή επιστροφής

Διαφάνειες που προστέθηκαν

## Παρατηρήσεις




```cpp
// Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Καλέστε τη μέθοδο AddFromHtml και μεταβιβάστε το αρχείο HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Χρησιμοποιήστε τη μέθοδο Save για να αποθηκεύσετε το αρχείο ως έγγραφο PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Τάξη [ISlide](../../islide/)
* Τάξη [String](../../../system/string/)
* Τάξη [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Τάξη [SlideCollection](../)
* Τάξη [TextReader](../../../system.io/textreader/)
* Τάξη [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)