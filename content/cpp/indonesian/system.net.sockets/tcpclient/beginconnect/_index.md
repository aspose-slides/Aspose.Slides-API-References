---
title: BeginConnect()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi koneksi secara asynchronous.
type: docs
weight: 261
url: /id/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Memulai operasi koneksi secara asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nama host remote. |
| port | **int32_t** | Port host remote. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna dan digunakan untuk mengidentifikasi secara unik setiap operasi koneksi asynchronous. |

### Nilai Kembali

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi koneksi asynchronous yang dimulai.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Memulai operasi koneksi secara asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Alamat IP dari host remote. |
| port | **int32_t** | Port host remote. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna dan digunakan untuk mengidentifikasi secara unik setiap operasi koneksi asynchronous. |

### Nilai Kembali

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi koneksi asynchronous yang dimulai.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Memulai operasi koneksi secara asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Alamat-alamat IP dari host remote. |
| port | **int32_t** | Port host remote. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna dan digunakan untuk mengidentifikasi secara unik setiap operasi koneksi asynchronous. |

### Nilai Kembali

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi koneksi asynchronous yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)