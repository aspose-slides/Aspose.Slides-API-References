---
title: ReadOnlySpan
second_title: Aspose.Slides for C++ API Referansı
description: Span sınıfı içinde kullanılmak için yönlendirme.
type: docs
weight: 1210
url: /tr/system/readonlyspan/
---
## ReadOnlySpan sınıfı

Forward to use within [Span](../span/) sınıfı.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü. Bu sınıf, nesnelerin ardışık dizileriyle yalnızca okuma modunda güvenli bir şekilde çalışmayı sağlar. Dizileri, yığın dizilerini veya ham işaretçileri sarmak için kullanılabilir ve sınır kontrolünü sürdürür. [ReadOnlySpan](./) işaret ettiği belleği sahiplenmez - sadece mevcut belleğe bir görünümdür. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Normal bir span'den yalnızca okuma span'i oluşturur. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Bir diziyi [ReadOnlySpan](./)'ye dönüştürür. |
## Açıklamalar

Represents a read-only contiguous region of arbitrary memory.

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)