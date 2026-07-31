---
title: Compare()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan objek Uri yang ditentukan menggunakan aturan perbandingan yang ditentukan.
type: docs
weight: 521
url: /id/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) metode

Membandingkan objek [Uri](../) yang ditentukan menggunakan aturan perbandingan yang ditentukan.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Komparan pertama |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Komparan kedua |
| partsToCompare | [UriComponents](../../uricomponents/) | Menentukan bagian-bagian **uri1** dan **uri2** yang akan dibandingkan |
| compareFormat | [UriFormat](../../uriformat/) | Menentukan pelarian karakter yang digunakan ketika komponen URI dibandingkan |
| comparisonType | [StringComparison](../../stringcomparison/) | Salah satu nilai StringComparison |

### Nilai Kembalian

Nilai negatif jika **uri1** kurang dari **uri2**; 0 jika **uri1** dan **uri2** **sama**; nilai positif jika **uri1** lebih besar dari **uri2**

## Lihat Juga

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)