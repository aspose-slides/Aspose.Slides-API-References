---
title: InsertFromHtml()
second_title: Aspose.Slides για την αναφορά API του C++
description: Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.
type: docs
weight: 209
url: /el/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο ανάκλησης που χρησιμοποιείται για την απόκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο ανάκλησης που χρησιμοποιείται για την απόκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν.

## SlideCollection::InsertFromHtml(int32_t, System::String) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο ανάκλησης που χρησιμοποιείται για την απόκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο ανάκλησης που χρησιμοποιείται για την απόκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο ανάκλησης που χρησιμοποιείται για την απόκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη. Εάν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Εάν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Διαφάνειες προστέθηκαν.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)