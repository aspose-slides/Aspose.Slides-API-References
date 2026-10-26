---
title: Write()
second_title: Aspose.Slides untuk C++ Referensi API
description: Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.
type: docs
weight: 53
url: /id/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte untuk ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array yang berisi byte untuk ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| N | Ukuran array stack |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Array stack yang berisi byte untuk ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method


Menulis subrentang byte yang ditentukan dari span byte yang ditentukan ke aliran.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Span byte untuk membaca byte yang ditulis |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)