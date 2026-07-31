---
title: Add()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan cookie ke koleksi.
type: docs
weight: 105
url: /id/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) metode

Menambahkan cookie ke koleksi.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie yang akan ditambahkan. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) metode

Menambahkan cookie ke koleksi.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie yang akan ditambahkan. |
| throwOnError | **bool** | Nilai yang menunjukkan apakah pengecualian akan dilempar ketika terjadi kesalahan. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) metode

Menyalin cookie dari koleksi yang ditentukan ke koleksi saat ini.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Koleksi yang akan disalin cookie-nya. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) metode

Menambahkan cookie untuk URI yang ditentukan.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie yang akan ditambahkan. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) metode

Menyalin cookie dari koleksi yang ditentukan untuk URI yang ditentukan ke koleksi saat ini.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Koleksi cookie yang akan disalin. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieContainer](../)
* Class [CookieCollection](../../cookiecollection/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)