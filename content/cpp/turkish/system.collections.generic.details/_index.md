---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 352
url: /tr/system.collections.generic.details/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | IEnumerable.Cast() ve IEnumerable.OfType() uzantı metodları tarafından kullanılan Enumerable. |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | IEnumerable.Select() uzantı metodu tarafından kullanılan Enumerable. |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | IEnumerable.Cast() uzantı metodu tarafından kullanılan Enumerator. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | IEnumerable.OfType() uzantı metodu tarafından kullanılan Enumerator. |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | IEnumerable.Select() uzantı metodu tarafından kullanılan Enumerator. |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Yapılar

| Yapı | Açıklama |
| --- | --- |
| [ComparerType](./comparertype/) | Elemanları 'less' semantiği kullanarak karşılaştırır. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Elemanları 'less' semantiği kullanarak karşılaştırır. |
| [has_method_compareto](./has_method_compareto/) | Belirtilen türde CompareTo metodunun var olup olmadığını kontrol eder. Varsa std::true_type, aksi takdirde std::false_type kalıtımını alır. std::enable_if içinde kullanılabilir. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Belirtilen türde CompareTo(SharedPtr<T>) metodunun var olup olmadığını kontrol eder. Varsa std::true_type, aksi takdirde std::false_type kalıtımını alır. std::enable_if içinde kullanılabilir. |
| [IsEqualExist](./isequalexist/) | Türün operator == sağladığını kontrol eder. |
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Dizin'in konteyner sınırları dışına çıkıp çıkmadığını, konteyner boyutu hariç tutularak kontrol eder. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Dizin'in konteyner sınırları dışına çıkıp çıkmadığını, konteyner boyutu hariç tutularak kontrol eder. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Dizin'in konteyner sınırları dışına çıkıp çıkmadığını, konteyner boyutu dahil edilerek kontrol eder. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Dizin'in konteyner sınırları dışına çıkıp çıkmadığını, konteyner boyutu dahil edilerek kontrol eder. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Belirli sınıfın operator == olup olmadığını belirlemek için yardımcı fonksiyon. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Belirli sınıfın operator == olup olmadığını belirlemek için yardımcı fonksiyon. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Koleksiyonun ilk elemanını almaya çalışır. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Koleksiyonun, koşul fonksiyonunu sağlayan ilk elemanını almaya çalışır. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Koleksiyonun son elemanını almaya çalışır. |
## Typedefs

| Typedef | Açıklama |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Operator == varlığını kontrol etmek için sahte typedef. |