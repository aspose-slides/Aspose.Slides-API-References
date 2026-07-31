---
title: BeginConnect()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi koneksi secara asynchronous.
type: docs
weight: 573
url: /id/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) method


Memulai operasi koneksi secara asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Titik akhir (endpoint) remote. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna untuk mengidentifikasi secara unik setiap operasi koneksi asynchronous. |

### Nilai Kembalian

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi koneksi asynchronous yang dimulai.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Memulai operasi koneksi secara asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nama host remote. |
| port | **int32_t** | Nomor port host remote. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna untuk mengidentifikasi secara unik setiap operasi koneksi asynchronous. |

### Nilai Kembalian

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi koneksi asynchronous yang dimulai.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Memulai operasi koneksi secara asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Alamat IP host remote. |
| port | **int32_t** | Nomor port host remote. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna untuk mengidentifikasi secara unik setiap operasi koneksi asynchronous. |

### Nilai Kembalian

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi koneksi asynchronous yang dimulai.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Memulai operasi koneksi secara asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Alamat IP host remote. |
| port | **int32_t** | Nomor port host remote. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna untuk mengidentifikasi secara unik setiap operasi koneksi asynchronous. |

### Nilai Kembalian

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi koneksi asynchronous yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [EndPoint](../../../system.net/endpoint/)
* Kelas [Object](../../../system/object/)
* Kelas [Socket](../)
* Kelas [String](../../../system/string/)
* Kelas [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)