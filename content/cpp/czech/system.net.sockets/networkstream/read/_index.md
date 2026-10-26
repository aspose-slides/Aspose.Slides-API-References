---
title: Read()
second_title: Aspose.Slides pro referenci API C++
description: Čte zadaný počet bajtů ze streamu a zapisuje je do určeného pole bajtů.
type: docs
weight: 196
url: /cs/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Čte určený počet bajtů ze streamu a zapisuje je do specifikovaného pole bajtů.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého budou zapsány přečtené bajty. |
| offset | **int32_t** | Posun v bajtech v daném poli. |
| size | **int32_t** | Počet bajtů k přečtení. |

### Návratová hodnota

Počet přečtených bajtů.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Čte určený počet bajtů ze streamu a zapisuje je do specifikovaného pole bajtů.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole bajtů, do kterého budou zapsány přečtené bajty. |
| offset | **int32_t** | Pozice 0-základní v **buffer**, kde začít zapisovat. |
| size | **int32_t** | Počet bajtů k přečtení |

### Návratová hodnota

Počet přečtených bajtů

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [NetworkStream](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)