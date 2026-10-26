---
title: IOControl()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan mode operasi tingkat rendah untuk socket.
type: docs
weight: 703
url: /id/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode


Menetapkan mode operasi tingkat rendah untuk socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ioControlCode | **int32_t** | Kode kontrol operasi yang akan dilakukan. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte yang berisi data masukan. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte yang berisi data keluaran. |

### Nilai Kembali

Jumlah byte dalam parameter **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode


Menetapkan mode operasi tingkat rendah untuk socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Kode kontrol operasi yang akan dilakukan. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte yang berisi data masukan. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte yang berisi data keluaran. |

### Nilai Kembali

Jumlah byte dalam parameter **optionOutValue**.

## Lihat Juga

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)