---
title: InsertFromHtml()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στην καθορισμένη θέση.
type: docs
weight: 157
url: /el/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο κλήσης επαναφοράς που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες.

## ISlideCollection::InsertFromHtml(int32_t, System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο κλήσης επαναφοράς που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Αντικείμενο TextReader που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο κλήσης επαναφοράς που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με το συγκεκριμένο δείκτη. Αν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Αν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlText | [System::String](../../../system/string/) | HTML προς προσθήκη. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο κλήσης επαναφοράς που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με το συγκεκριμένο δείκτη. Αν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Αν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με το συγκεκριμένο δείκτη. Αν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Αν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) μέθοδος


Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Θέση εισαγωγής. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο κλήσης επαναφοράς που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | [System::String](../../../system/string/) | Ένα URI του συγκεκριμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| useSlideWithIndexAsStart | **bool** | Αυτή η σημαία καθορίζει πώς να ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με το συγκεκριμένο δείκτη. Αν **true**, η εισαγωγή δεδομένων θα ξεκινήσει από κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη. Αν **false**, τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |

### Τιμή Επιστροφής

Προστιθέμενες διαφάνειες.

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