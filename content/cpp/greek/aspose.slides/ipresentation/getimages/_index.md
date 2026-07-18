---
title: GetImages()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει αντικείμενα εικόνας μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης.
type: docs
weight: 417
url: /el/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method


Επιστρέφει αντικείμενα εικόνας μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |

### Τιμή επιστροφής

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method


Επιστρέφει αντικείμενα Bitmap μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |

### Τιμή επιστροφής

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Επιστρέφει αντικείμενα εικόνας μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| scaleX | **float** | Η τιμή με την οποία θα κλιμακωθεί αυτή η μικρογραφία στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή με την οποία θα κλιμακωθεί αυτή η μικρογραφία στην κατεύθυνση του άξονα y. |

### Τιμή επιστροφής

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method


Επιστρέφει αντικείμενα εικόνας μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλίμακα.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| scaleX | **float** | Η τιμή με την οποία θα κλιμακωθεί αυτή η μικρογραφία στην κατεύθυνση του άξονα x. |
| scaleY | **float** | Η τιμή με την οποία θα κλιμακωθεί αυτή η μικρογραφία στην κατεύθυνση του άξονα y. |

### Τιμή επιστροφής

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Επιστρέφει αντικείμενα εικόνας μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή επιστροφής

Bitmap objects.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method


Επιστρέφει αντικείμενα εικόνας μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

### Τιμή επιστροφής

Bitmap objects.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../iimage/)
* Κλάση [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Κλάση [IPresentation](../)
* Κλάση [Size](../../../system.drawing/size/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)