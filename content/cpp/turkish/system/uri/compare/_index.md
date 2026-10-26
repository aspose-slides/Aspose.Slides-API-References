---
title: Compare()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen Uri nesnelerini belirtilen karşılaştırma kurallarını kullanarak karşılaştırır.
type: docs
weight: 521
url: /tr/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) metodu


Belirtilen [Uri](../) nesnelerini belirtilen karşılaştırma kurallarını kullanarak karşılaştırır.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | İlk karşılaştırılan |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | İkinci karşılaştırılan |
| partsToCompare | [UriComponents](../../uricomponents/) | **uri1** ve **uri2**'nin karşılaştırılacak bölümlerini belirtir |
| compareFormat | [UriFormat](../../uriformat/) | URI bileşenleri karşılaştırılırken kullanılan karakter kaçışını belirtir |
| comparisonType | [StringComparison](../../stringcomparison/) | StringComparison değerlerinden biri |

### Dönüş Değeri

**uri1** **uri2**'den küçükse negatif bir değer; **uri1** ve **uri2** eşitse 0; **uri1** **uri2**'den büyükse pozitif bir değer

## İlgili

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)