---
title: Bitmap()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen mevcut görüntüden yeni bir Bitmap nesnesi oluşturur.
type: docs
weight: 1
url: /tr/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) yapıcı


Belirtilen mevcut görüntüden yeni bir [Bitmap](../) nesnesi oluşturur.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bitmap görüntüsü oluşturulacak mevcut görüntü |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) yapıcı


Belirtilen akıştan yeni bir [Bitmap](../) nesnesi oluşturur.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Görüntü verisini içeren bir akış |
| useIcm | **bool** | YOK SAYILDI |

## Bitmap::Bitmap(const String\&) yapıcı


Belirtilen dosyadan yeni bir [Bitmap](../) nesnesi oluşturur.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Görüntü verisini içeren dosyanın adı |

## Bitmap::Bitmap(const String\&, bool) yapıcı


Belirtilen dosyadan yeni bir [Bitmap](../) nesnesi oluşturur.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Görüntü verisini içeren dosyanın adı |
| useIcm | **bool** | YOK SAYILDI |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) yapıcı


Belirtilen genişlik, yükseklik, piksel biçimi ve piksel verisiyle bir bitmap görüntüsü temsil eden yeni bir [Bitmap](../) nesnesi oluşturur.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Görüntünün genişliği |
| height | int | Görüntünün yüksekliği |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Görüntünün piksel biçimi |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) yapıcı


Belirtilen mevcut görüntüden, belirtilen boyuta ölçeklendirilmiş yeni bir [Bitmap](../) nesnesi oluşturur.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bitmap görüntüsü oluşturulacak mevcut görüntü |
| size | const [Size](../../size/)\& | Yeni görüntünün boyutu |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) yapıcı


Belirtilen mevcut görüntüden, genişliği ve yüksekliği belirtilen değerlere ölçeklendirilmiş yeni bir [Bitmap](../) nesnesi oluşturur.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bitmap görüntüsü oluşturulacak mevcut görüntü |
| width | int | Yeni görüntünün genişliği |
| height | int | Yeni görüntünün yüksekliği |

## İlgili

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Image](../../image/)
* Sınıf [Bitmap](../)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [String](../../../system/string/)
* Sınıf [Size](../../size/)
* İsim Uzayı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)