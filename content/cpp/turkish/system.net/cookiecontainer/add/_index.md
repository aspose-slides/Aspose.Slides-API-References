---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyona bir çerez ekler.
type: docs
weight: 105
url: /tr/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) yöntemi


Koleksiyona bir çerez ekler.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Eklenecek çerez. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) yöntemi


Koleksiyona bir çerez ekler.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Eklenecek çerez. |
| throwOnError | **bool** | Bir hata oluştuğunda bir istisna atılıp atılmayacağını belirten değer. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) yöntemi


Belirtilen koleksiyondan mevcut koleksiyona çerezleri kopyalar.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Çerezlerin kopyalanacağı koleksiyon. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) yöntemi


Belirtilen URI için bir çerez ekler.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Çerezin URI'si. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Eklenecek çerez. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) yöntemi


Belirtilen URI için belirtilen koleksiyondan çerezleri mevcut koleksiyona kopyalar.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Çerezin URI'si. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Çerezlerin kopyalanacağı çerez koleksiyonu. |

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Cookie](../../cookie/)
* Sınıf [CookieContainer](../)
* Sınıf [CookieCollection](../../cookiecollection/)
* Sınıf [Uri](../../../system/uri/)
* AdAlanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)