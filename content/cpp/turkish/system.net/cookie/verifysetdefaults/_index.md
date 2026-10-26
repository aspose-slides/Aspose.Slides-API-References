---
title: VerifySetDefaults()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan öznitelik değerlerini doğrular ve ayarlar.
type: docs
weight: 482
url: /tr/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) metot

Varsayılan öznitelik değerlerini doğrular ve ayarlar.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Çerezin tanımı. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | İç alanları başlatmak için kullanılan Uri sınıfı örneği. |
| isLocalDomain | **bool** | Çerezin yerel domaine itildiğini gösteren bir değer. |
| localDomain | [String](../../../system/string/) | Yerel bir domain adı. |
| setDefault | **bool** | Çerezin özniteliklerinin varsayılan değerleriyle başlatılması gerektiğini gösteren bir değer. |
| shouldThrow | **bool** | Belirtilen değerler geçersiz olduğunda bir istisna atılması gerekip gerekmediğini gösteren bir değer. |

### Dönüş Değeri

Tüm değerler geçerli olduğunda true, aksi takdirde false.

## İlgili

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [Cookie](../)
* İsim Alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)