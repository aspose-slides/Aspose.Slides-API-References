---
title: TryCreate()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI'yi temsil eden bir Uri nesnesi oluşturur; bir argüman URI türünü belirtir.
type: docs
weight: 508
url: /tr/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) metodu


Belirtilen URI'yi temsil eden bir [Uri](../) nesnesi oluşturur; bir argüman URI türünü belirtir.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Oluşturulan nesne tarafından temsil edilecek dize URI |
| uriKind | [UriKind](../../urikind/) | URI türünü belirtir |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | İnşa başarılı olursa, metodun dönüşünde yeni oluşturulan [Uri](../) nesnesine işaret eden çıktı argümanı |

### Dönüş Değeri

İnşa başarılı ise true, aksi takdirde false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) metodu


Belirtilen [Uri](../) nesnesi (temel URI'yi temsil eden) ve göreceli URI'nin dize temsili kullanılarak bir [Uri](../) nesnesi oluşturur.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Temel URI |
| relativeUri | const [String](../../string/)\& | Temel URI'ye eklenen göreceli URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | İnşa başarılı olursa, metodun dönüşünde yeni oluşturulan [Uri](../) nesnesine işaret eden çıktı argümanı |

### Dönüş Değeri

İnşa başarılı ise true, aksi takdirde false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) metodu


Belirtilen temel ve göreceli URI'lerden bir [Uri](../) nesnesi oluşturur.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Temel URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Temel URI'ye eklenen göreceli URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | İnşa başarılı olursa, metodun dönüşünde yeni oluşturulan [Uri](../) nesnesine işaret eden çıktı argümanı |

### Dönüş Değeri

İnşa başarılı ise true, aksi takdirde false

## İlgili

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Uri](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)