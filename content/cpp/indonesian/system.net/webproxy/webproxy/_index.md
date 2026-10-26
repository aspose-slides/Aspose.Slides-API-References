---
title: WebProxy()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru.
type: docs
weight: 131
url: /id/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Alamat server proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Alamat server proxy. |
| BypassOnLocal | **bool** | Nilai yang menunjukkan apakah server proxy harus digunakan untuk alamat lokal. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Alamat server proxy. |
| BypassOnLocal | **bool** | Nilai yang menunjukkan apakah server proxy harus digunakan untuk alamat lokal. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Daftar alamat yang tidak menggunakan server proxy. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Alamat server proxy. |
| BypassOnLocal | **bool** | Nilai yang menunjukkan apakah server proxy harus digunakan untuk alamat lokal. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Daftar alamat yang tidak menggunakan server proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Kredensial yang dikirim ke server proxy untuk autentikasi. |

## WebProxy::WebProxy(String, int32_t) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Nama host. |
| Port | **int32_t** | Nomor port. |

## WebProxy::WebProxy(String) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Alamat server proxy. |

## WebProxy::WebProxy(String, bool) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Alamat server proxy. |
| BypassOnLocal | **bool** | Nilai yang menunjukkan apakah server proxy harus digunakan untuk alamat lokal. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Alamat server proxy. |
| BypassOnLocal | **bool** | Nilai yang menunjukkan apakah server proxy harus digunakan untuk alamat lokal. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Daftar alamat yang tidak menggunakan server proxy. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Alamat server proxy. |
| BypassOnLocal | **bool** | Nilai yang menunjukkan apakah server proxy harus digunakan untuk alamat lokal. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Daftar alamat yang tidak menggunakan server proxy. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Kredensial yang dikirim ke server proxy untuk autentikasi. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)