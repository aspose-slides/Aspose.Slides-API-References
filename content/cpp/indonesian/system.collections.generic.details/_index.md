---
title: "System::Collections::Generic::Details"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 352
url: /id/system.collections.generic.details/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable yang digunakan oleh metode ekstensi IEnumerable.Cast() dan IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable yang digunakan oleh metode ekstensi IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator yang digunakan oleh metode ekstensi IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator yang digunakan oleh metode ekstensi IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator yang digunakan oleh metode ekstensi IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Struktur

| Struktur | Deskripsi |
| --- | --- |
| [ComparerType](./comparertype/) | Membandingkan elemen menggunakan semantik 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Membandingkan elemen menggunakan semantik 'less'. |
| [has_method_compareto](./has_method_compareto/) | Memeriksa apakah metode CompareTo ada dalam tipe yang ditentukan. Jika ada, mewarisi std::true_type, jika tidak mewarisi std::false_type. Dapat digunakan dalam std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Memeriksa apakah metode CompareTo(SharedPtr<T>) ada dalam tipe yang ditentukan. Jika ada, mewarisi std::true_type, jika tidak mewarisi std::false_type. Dapat digunakan dalam std::enable_if. |
| [IsEqualExist](./isequalexist/) | Memeriksa apakah tipe menyediakan operator ==. |
## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Memeriksa apakah indeks berada di luar batas kontainer, tidak termasuk ukuran kontainer. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Memeriksa apakah indeks berada di luar batas kontainer, tidak termasuk ukuran kontainer. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Memeriksa apakah indeks berada di luar batas kontainer, termasuk ukuran kontainer. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Memeriksa apakah indeks berada di luar batas kontainer, termasuk ukuran kontainer. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Fungsi bantuan untuk menentukan apakah kelas tertentu memiliki operator ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Fungsi bantuan untuk menentukan apakah kelas tertentu memiliki operator ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Mencoba mengambil elemen pertama dari koleksi. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Mencoba mengambil elemen pertama dari koleksi yang memenuhi fungsi predikat. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Mencoba mengambil elemen terakhir dari koleksi. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Typedef dummy untuk memeriksa keberadaan operator ==. |