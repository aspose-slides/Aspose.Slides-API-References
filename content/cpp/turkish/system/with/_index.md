---
title: With()
second_title: Aspose.Slides için C++ API Referansı
description: Referans kaydını klonlar ve başlatıcı fonktörü ona uygular.
type: docs
weight: 2614
url: /tr/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) fonksiyon


Referans kaydını klonlar ve başlatıcı funktörü ona uygular.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Klonlanacak kayıt türü. |
| A | Başlatıcı funktör türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Klonlanacak ve başlatılacak nesneye ait paylaşımlı işaretçi. |
| initializer | const A\& | Kayıt klonuna uygulanacak başlatıcı funktör. |

### Dönüş Değeri

Klonlanmış kayda ait paylaşımlı işaretçi.

## System::With(const T\&, const A\&) fonksiyon


Yapı kaydını kopyalar ve başlatıcı funktörü ona uygular.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Kopyalanacak kayıt türü. |
| A | Başlatıcı funktör türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | const T\& | Kopyalanacak ve başlatılacak kayıt. |
| initializer | const A\& | Kayıt kopyasına uygulanacak başlatıcı funktör. |

### Dönüş Değeri

Kopyalanmış kayıt.

## Diğer Bağlantılar

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)