---
title: AddImage()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει μια εικόνα σε μια παρουσίαση.
type: docs
weight: 14
url: /el/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) μέθοδος


Προσθέτει μια εικόνα στην παρουσίαση.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Εικόνα προς προσθήκη. |

### Τιμή επιστροφής

Η εικόνα προστέθηκε.
## Σχόλια


Αυτή η μέθοδος μετατρέπει τα μετααρχεία WMF/EMF σε ραστερ εικόνα PNG πριν την εισαγωγή στην παρουσίαση.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) μέθοδος


Προσθέτει εικόνα από ροή μνήμης.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Ροή μνήμης. |

### Τιμή επιστροφής

Η εικόνα προστέθηκε.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) μέθοδος


Προσθέτει μια εικόνα στην παρουσίαση από ροή.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία θα προστεθεί η εικόνα. |

### Τιμή επιστροφής

Η εικόνα προστέθηκε.
## Σχόλια


Αυτή η μέθοδος μπορεί να προσθέσει μετααρχεία WMF/EMF σε μια παρουσίαση χωρίς να τα μετατρέψει σε ραστερ εικόνα PNG.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) μέθοδος


Δημιουργεί και προσθέτει μια εικόνα στην παρουσίαση από ροή.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία θα προστεθεί το αρχείο εικόνας. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

### Τιμή επιστροφής

Προστέθηκε [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) μέθοδος


Προσθέτει μια εικόνα στην παρουσίαση από καθορισμένη ενδιάμεση μνήμη.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ενδιάμεση μνήμη. |

### Τιμή επιστροφής

Η εικόνα προστέθηκε.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) μέθοδος


Προσθέτει ένα αντίγραφο μιας εικόνας από άλλη παρουσίαση.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Πηγή εικόνας. |

### Τιμή επιστροφής

Η εικόνα προστέθηκε.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) μέθοδος


Προσθέτει μια εικόνα στην παρουσίαση από αντικείμενο SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Αντικείμενο εικόνας SVG [ISvgImage](../../isvgimage/) |

### Τιμή επιστροφής

Η εικόνα προστέθηκε.

## Δείτε επίσης

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)