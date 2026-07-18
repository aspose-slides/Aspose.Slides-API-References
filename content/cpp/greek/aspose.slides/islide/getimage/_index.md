---
title: GetImage()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει ένα αντικείμενο εικόνας με προσαρμοσμένη κλιμάκωση.
type: docs
weight: 105
url: /el/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) μέθοδος

Επιστρέφει ένα αντικείμενο εικόνας με προσαρμοσμένη κλιμάκωση.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή Επιστροφής

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Τιμή Επιστροφής

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) μέθοδος

Επιστρέφει ένα αντικείμενο εικόνας με συγκεκριμένο μέγεθος.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή Επιστροφής

Bitmap object.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail tiff bitmap με καθορισμένες παραμέτρους.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Παράμετροι Tiff. |

### Τιμή Επιστροφής

Image object.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Παράμετροι Rendering. |

### Τιμή Επιστροφής

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Bitmap με προσαρμοσμένη κλιμάκωση.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Παράμετροι Rendering. |
| scaleX | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή Επιστροφής

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) μέθοδος

Επιστρέφει ένα αντικείμενο Thumbnail Bitmap με καθορισμένο μέγεθος.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Παράμετροι Rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή Επιστροφής

Bitmap objects.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../iimage/)
* Κλάση [ISlide](../)
* Κλάση [Size](../../../system.drawing/size/)
* Κλάση [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Κλάση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)