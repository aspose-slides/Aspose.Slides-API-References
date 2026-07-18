---
title: Save()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο αρχείο σε μορφή PNG.
type: docs
weight: 1
url: /el/system.drawing/image/save/
---
## Image::Save(const String\&) μέθοδος

Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο αρχείο σε μορφή PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Το όνομα του αρχείου στο οποίο θα αποθηκευθεί η εικόνα |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) μέθοδος

Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο αρχείο στην καθορισμένη μορφή.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Το όνομα του αρχείου στο οποίο θα αποθηκευθεί η εικόνα |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Μια μορφή για την αποθήκευση της εικόνας |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) μέθοδος

Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στη συγκεκριμένη ροή στην καθορισμένη μορφή.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Μια ροή για την αποθήκευση της εικόνας |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Μια μορφή για την αποθήκευση της εικόνας |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) μέθοδος

Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στο καθορισμένο αρχείο χρησιμοποιώντας τον καθορισμένο κωδικοποιητή και τις παραμέτρους του κωδικοποιητή.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Το όνομα του αρχείου στο οποίο θα αποθηκευθεί η εικόνα |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Ο κωδικοποιητής που θα χρησιμοποιηθεί |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Οι παράμετροι του κωδικοποιητή που θα χρησιμοποιηθούν |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) μέθοδος

Αποθηκεύει την εικόνα που αντιπροσωπεύει το τρέχον αντικείμενο στη συγκεκριμένη ροή χρησιμοποιώντας τον καθορισμένο κωδικοποιητή και τις παραμέτρους του κωδικοποιητή.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Μια ροή για την αποθήκευση της εικόνας |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Ο κωδικοποιητής που θα χρησιμοποιηθεί |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Οι παράμετροι του κωδικοποιητή που θα χρησιμοποιηθούν |

## Δείτε επίσης

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [String](../../../system/string/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)