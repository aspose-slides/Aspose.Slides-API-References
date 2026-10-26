---
title: AddFromHtml()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.
type: docs
weight: 144
url: /el/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML για προσθήκη. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Διαφάνειες που προστέθηκαν.

## ISlideCollection::AddFromHtml(System::String) μέθοδος

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML για προσθήκη. |

### Τιμή Επιστροφής

Διαφάνειες που προστέθηκαν.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Διαφάνειες που προστέθηκαν.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) μέθοδος

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

### Τιμή Επιστροφής

Διαφάνειες που προστέθηκαν.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Διαφάνειες που προστέθηκαν.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) μέθοδος

Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

### Τιμή Επιστροφής

Διαφάνειες που προστέθηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlide](../../islide/)
* Κλάση [String](../../../system/string/)
* Κλάση [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Κλάση [ISlideCollection](../)
* Κλάση [TextReader](../../../system.io/textreader/)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)