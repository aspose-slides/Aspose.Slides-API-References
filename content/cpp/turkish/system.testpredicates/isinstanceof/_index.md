---
title: IsInstanceOf()
second_title: Aspose.Slides for C++ API Referansı
description: Is-instance-of, IsInstanceOf doğrulama çevirisi için argümanları karşılaştırır.
type: docs
weight: 118
url: /tr/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) function


Is-instance-of, IsInstanceOf doğrulama çevirisi için argümanları karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Argüman tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Bir typeInfo nesnesi, **obj** nin türünün karşılaştırılacağı türü temsil eder |
| obj | const T\& | Belirtilen türle karşılaştırılacak nesnenin türüne sahip bir nesne |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## İlgili

* Sınıf [TypeInfo](../../system/typeinfo/)
* Ad alanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)