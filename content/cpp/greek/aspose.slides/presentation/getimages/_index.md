---
title: GetImages()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει αντικείμενα Image για όλες τις διαφάνειες μιας παρουσίασης.
type: docs
weight: 456
url: /el/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) μέθοδος

Επιστρέφει αντικείμενα Image για όλες τις διαφάνειες μιας παρουσίασης.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές Tiff. |

### Τιμή Επιστροφής

Αντικείμενα Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) μέθοδος

Επιστρέφει αντικείμενα Thumbnail Image για συγκεκριμένες διαφάνειες μιας παρουσίασης.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |

### Τιμή Επιστροφής

Αντικείμενα Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) μέθοδος

Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές Tiff. |
| scaleX | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή Επιστροφής

Αντικείμενα Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) μέθοδος

Επιστρέφει αντικείμενα Thumbnail Image για συγκεκριμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| scaleX | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή με την οποία κλιμακώνεται αυτή η Thumbnail στην κατεύθυνση του άξονα y. |

### Τιμή Επιστροφής

Αντικείμενα Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) μέθοδος

Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας για δημιουργία. |

### Τιμή Επιστροφής

Αντικείμενα Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) μέθοδος

Επιστρέφει αντικείμενα Thumbnail Image για συγκεκριμένες διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Επιλογές Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Πίνακας με θέσεις διαφανειών, ξεκινώντας από 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας για δημιουργία. |

### Τιμή Επιστροφής

Αντικείμενα Image.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../iimage/)
* Κλάση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Κλάση [Presentation](../)
* Κλάση [Size](../../../system.drawing/size/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)