---
title: CreateHttp()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru dari kelas WebRequest menggunakan URI yang ditentukan.
type: docs
weight: 79
url: /id/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) metode

Membuat instance baru dari [WebRequest](../) kelas menggunakan URI yang ditentukan.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | URI yang digunakan untuk membuat instance baru dari [WebRequest](../) kelas. |

### Nilai Kembalian

Sebuah instance WebRequest-kelas yang baru dibuat.

## Catatan

NotSupportedException akan dilemparkan ketika URI yang ditentukan dimulai dengan skema apa pun kecuali [http://](http://) atau [https://](https://).

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) metode

Membuat instance baru dari [WebRequest](../) kelas menggunakan URI yang ditentukan.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI yang digunakan untuk membuat instance baru dari [WebRequest](../) kelas. |

### Nilai Kembalian

Sebuah instance WebRequest-kelas yang baru dibuat.

## Catatan

NotSupportedException akan dilemparkan ketika URI yang ditentukan dimulai dengan skema apa pun kecuali [http://](http://) atau [https://](https://).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)