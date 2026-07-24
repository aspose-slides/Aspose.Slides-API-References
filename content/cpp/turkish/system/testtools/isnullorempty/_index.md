---
title: IsNullOrEmpty()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun null veya boş olup olmadığını denetler.
type: docs
weight: 27
url: /tr/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) metot

Koleksiyonun null veya boş olup olmadığını kontrol eder.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Koleksiyon tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Kontrol edilecek koleksiyon. |

### Dönüş Değeri

True if collection is null or has zero element count, false otherwise.

## TestTools::IsNullOrEmpty(const System::String\&) metot

Dizgenin null veya boş olup olmadığını kontrol eder.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) to check. |

### Dönüş Değeri

True if string is null or has zero length, false otherwise.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Yapı [TestTools](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)