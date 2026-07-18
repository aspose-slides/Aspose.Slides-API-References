---
title: Bitmap()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα νέο αντικείμενο Bitmap από την καθορισμένη υπάρχουσα εικόνα.
type: docs
weight: 1
url: /el/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor

Δημιουργεί ένα νέο αντικείμενο [Bitmap](../) από την καθορισμένη υπάρχουσα εικόνα.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η υπάρχουσα εικόνα από την οποία θα δημιουργηθεί η bitmap εικόνα |
 
## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor

Δημιουργεί ένα νέο αντικείμενο [Bitmap](../) από το καθορισμένο ρεύμα.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Ένα ρεύμα που περιέχει δεδομένα εικόνας |
| useIcm | **bool** | ΑΓΝΟΕΙΤΑΙ |

## Bitmap::Bitmap(const String\&) constructor

Δημιουργεί ένα νέο αντικείμενο [Bitmap](../) από το καθορισμένο αρχείο.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Το όνομα του αρχείου που περιέχει δεδομένα εικόνας |

## Bitmap::Bitmap(const String\&, bool) constructor

Δημιουργεί ένα νέο αντικείμενο [Bitmap](../) από το καθορισμένο αρχείο.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Το όνομα του αρχείου που περιέχει δεδομένα εικόνας |
| useIcm | **bool** | ΑΓΝΟΕΙΤΑΙ |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor

Δημιουργεί ένα νέο αντικείμενο [Bitmap](../) που αντιπροσωπεύει μια bitmap εικόνα με το καθορισμένο πλάτος, ύψος, μορφή εικονοστοιχείου και δεδομένα εικονοστοιχείου.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Το πλάτος της εικόνας |
| height | int | Το ύψος της εικόνας |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Η μορφή εικονοστοιχείου της εικόνας |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor

Δημιουργεί ένα νέο αντικείμενο [Bitmap](../) από την καθορισμένη υπάρχουσα εικόνα, κλιμακωμένο στο καθορισμένο μέγεθος.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η υπάρχουσα εικόνα από την οποία θα δημιουργηθεί η bitmap εικόνα |
| size | const [Size](../../size/)\& | Το μέγεθος της νέας εικόνας |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor

Δημιουργεί ένα νέο αντικείμενο [Bitmap](../) από την καθορισμένη υπάρχουσα εικόνα με πλάτος και ύψος κλιμακωμένα στις καθορισμένες τιμές.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η υπάρχουσα εικόνα από την οποία θα δημιουργηθεί η bitmap εικόνα |
| width | int | Πλάτος της νέας εικόνας |
| height | int | Ύψος της νέας εικόνας |

## See Also

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)