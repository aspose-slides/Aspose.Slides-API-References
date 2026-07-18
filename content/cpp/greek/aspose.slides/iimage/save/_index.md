---
title: Save()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποθηκεύει την εικόνα σε αρχείο.
type: docs
weight: 40
url: /el/aspose.slides/iimage/save/
---
## IImage::Save(System::String) μέθοδος


Αποθηκεύει την εικόνα σε αρχείο.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |

## IImage::Save(System::String, ImageFormat) μέθοδος


Αποθηκεύει την εικόνα σε αρχείο με την καθορισμένη μορφή.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |
| format | [ImageFormat](../../imageformat/) | Η μορφή της εικόνας. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) μέθοδος


Αποθηκεύει την εικόνα σε ροή με την καθορισμένη μορφή.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Η ροή όπου θα αποθηκευτεί η εικόνα. |
| format | [ImageFormat](../../imageformat/) | Η μορφή της εικόνας. |

## IImage::Save(System::String, ImageFormat, int32_t) μέθοδος


Αποθηκεύει την εικόνα σε αρχείο με την καθορισμένη μορφή και ποιότητα.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |
| format | [ImageFormat](../../imageformat/) | Η μορφή της εικόνας. |
| quality | **int32_t** | Η ποιότητα της αποθηκευμένης εικόνας (0 έως 100).  Αυτό το πεδίο επηρεάζει μόνο την αποθήκευση σε [ImageFormat::Jpeg](../../imageformat/)· για όλες τις άλλες μορφές, αγνοείται. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) μέθοδος


Αποθηκεύει την εικόνα σε ροή με την καθορισμένη μορφή και ποιότητα.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Η ροή όπου θα αποθηκευτεί η εικόνα. |
| format | [ImageFormat](../../imageformat/) | Η μορφή της εικόνας. |
| quality | **int32_t** | Η ποιότητα της αποθηκευμένης εικόνας (0 έως 100).  Αυτό το πεδίο επηρεάζει μόνο την αποθήκευση σε [ImageFormat::Jpeg](../../imageformat/)· για όλες τις άλλες μορφές, αγνοείται. |

## Δείτε επίσης

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [IImage](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)