---
title: AddImage()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα αντίγραφο μιας εικόνας από μια άλλη παρουσίαση.
type: docs
weight: 53
url: /el/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method

Προσθέτει ένα αντίγραφο μιας εικόνας από μια άλλη παρουσίαση.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Πηγαία εικόνα. |

### Τιμή επιστροφής

Προστέθηκε η εικόνα.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) method

Προσθέτει μια εικόνα σε μια παρουσίαση.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Εικόνα για προσθήκη. |

### Τιμή επιστροφής

Προστέθηκε η εικόνα.

## Παρατηρήσεις

Αυτή η μέθοδος μετατρέπει αρχεία metafile WMF/EMF σε raster PNG εικόνα πριν τα ενσωματώσει σε παρουσίαση.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method

Προσθέτει μια εικόνα σε μια παρουσίαση από ροή.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Ροή από την οποία θα προστεθεί η εικόνα. |

### Τιμή επιστροφής

Προστέθηκε η εικόνα.

## Παρατηρήσεις

Αυτή η μέθοδος μπορεί να προσθέσει αρχεία metafile WMF/EMF σε μια παρουσίαση χωρίς να τα μετατρέπει σε raster PNG εικόνα.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) method

Προσθέτει μια εικόνα σε μια παρουσίαση από ροή.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία θα προστεθεί η εικόνα. |

### Τιμή επιστροφής

Προστέθηκε η εικόνα.

## Παρατηρήσεις

Αυτή η μέθοδος μπορεί να προσθέσει αρχεία metafile WMF/EMF σε μια παρουσίαση χωρίς να τα μετατρέπει σε raster PNG εικόνα.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Δημιουργεί και προσθέτει μια εικόνα σε μια παρουσίαση από ροή.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία θα προστεθεί το αρχείο εικόνας. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

### Τιμή επιστροφής

Προστέθηκε [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method

Προσθέτει μια εικόνα σε μια παρουσίαση από καθορισμένο buffer.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Τιμή επιστροφής

Προστέθηκε η εικόνα.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method

Προσθέτει μια εικόνα σε μια παρουσίαση από αντικείμενο Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Αντικείμενο εικόνας Svg [ISvgImage](../../isvgimage/) |

### Τιμή επιστροφής

Προστέθηκε η εικόνα.

## Δείτε επίσης

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)