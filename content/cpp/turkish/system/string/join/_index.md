---
title: Join()
second_title: Aspose.Slides for C++ API Referansı
description: Diziyi ayırıcı olarak string kullanarak birleştirir.
type: docs
weight: 846
url: /tr/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) metot

Diziyi ayırıcı olarak string kullanarak birleştirir.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) dizi öğeleri arasında birleştirirken koymak için. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) birleştirilecek parçalar. |
| startIndex | int | Birleştirmenin başlayacağı dizideki ilk indeks. |
| count | int | Birleştirilecek dizi öğelerinin sayısı. -1, 'dizi sonuna kadar' anlamına gelir. |

### Dönüş Değeri

[String](../) birleşik dizi öğelerini temsil eder.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) metot

Diziyi ayırıcı olarak string kullanarak birleştirir.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) dizi öğeleri arasında birleştirirken koymak için. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | Birleştirilecek parçaların ArrayView'i. |
| startIndex | int | Birleştirmenin başlayacağı dizideki ilk indeks. |
| count | int | Birleştirilecek dizi öğelerinin sayısı. -1, 'dizi sonuna kadar' anlamına gelir. |

### Dönüş Değeri

[String](../) birleşik dizi öğelerini temsil eder.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) metot

Diziyi ayırıcı olarak string kullanarak birleştirir.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) dizi öğeleri arasında birleştirirken koymak için. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - parçalar enumerable nesnesi |
 
### Dönüş Değeri

[String](../) birleşik öğeleri temsil eder.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) metot

Diziyi ayırıcı olarak string kullanarak birleştirir.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) dizi öğeleri arasında birleştirirken koymak için. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) birleştirilecek parçalar. |

### Dönüş Değeri

[String](../) birleşik öğeleri temsil eder.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)