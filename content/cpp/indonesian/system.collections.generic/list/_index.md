---
title: List
second_title: Referensi API Aspose.Slides untuk C++
description: Deklarasi maju List.
type: docs
weight: 430
url: /id/system.collections.generic/list/
---
## List kelas

[List](./) deklarasi maju.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Spesifik C++. |
| void [Add](./add/)(const T\&) override | Menambahkan elemen ke akhir daftar. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Menambahkan elemen ke daftar; digunakan saat menerjemahkan inisialisator. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Menambahkan semua elemen dari koleksi (atau dirinya sendiri) ke akhir daftar saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Mendapatkan referensi hanya-baca ke koleksi ini. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Mendapatkan iterator ke elemen pertama koleksi. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Mendapatkan iterator ke elemen pertama dari koleksi yang bersifat const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Mencari item dalam daftar terurut. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Mencari item dalam daftar terurut. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Mencari item dalam daftar terurut. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Mendapatkan iterator ke elemen pertama yang bersifat const dari koleksi. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Mendapatkan iterator untuk elemen const yang tidak ada di belakang akhir koleksi. |
| void [Clear](./clear/)() override | Menghapus semua elemen. |
| **bool** [Contains](./contains/)(const T\&) const override | Memeriksa apakah item ada dalam daftar. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Membuat daftar elemen yang dikonversi ke tipe berbeda. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Menyalin elemen daftar ke elemen array yang ada. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Menyalin semua elemen ke elemen array yang ada. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Menyalin elemen mulai dari indeks yang ditentukan ke elemen array yang ada. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Mendapatkan iterator terbalik ke elemen const terakhir dari koleksi (pertama dalam urutan terbalik). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Mendapatkan iterator terbalik untuk elemen const yang tidak ada sebelum awal koleksi. |
| [vector_t](./vector_t/)\& [data](./data/)() | Fungsi akses struktur data dasar. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Fungsi akses struktur data dasar. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Mendapatkan iterator untuk elemen yang tidak ada di belakang akhir koleksi. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Mendapatkan iterator untuk elemen yang tidak ada di belakang akhir koleksi yang bersifat const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Memeriksa apakah elemen yang memenuhi predikat tertentu ada dalam daftar. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen terakhir yang memenuhi predikat tertentu. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Menerapkan aksi pada semua elemen dalam daftar. |
| int [get_Capacity](./get_capacity/)() const | Mendapatkan kapasitas daftar saat ini. |
| int [get_Count](./get_count/)() const override | Mendapatkan jumlah elemen dalam daftar saat ini. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Memeriksa apakah koleksi berukuran tetap. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Memeriksa apakah koleksi hanya-baca. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Mendapatkan objek yang menjadi sinkronisasi koleksi. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Mendapatkan enumerator untuk mengiterasi elemen daftar. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Membuat irisan daftar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Konstruktor default. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Konstruktor salin. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Konstruktor pindah. |
| T [idx_get](./idx_get/)(int) const override | Mendapatkan elemen pada posisi tertentu. |
| void [idx_set](./idx_set/)(int, T) override | Menetapkan elemen pada posisi tertentu. |
| int [IndexOf](./indexof/)(const T\&) const override | Mendapatkan indeks pertama dari item tertentu. |
| int [IndexOf](./indexof/)(const T\&, int) const | Mencari item tertentu dalam daftar. |
| void [Insert](./insert/)(int, const T\&) override | Menyisipkan item pada posisi yang ditentukan. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Menyisipkan rentang data pada posisi tertentu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam seluruh daftar. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam rentang elemen di [List](./) yang memperluas dari elemen pertama hingga indeks yang ditentukan. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam rentang elemen di [List](./) yang berisi sejumlah elemen tertentu dan berakhir pada indeks yang ditentukan. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Menerapkan fungsi akumulator pada urutan. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Menentukan apakah semua elemen dalam urutan memenuhi kondisi. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Menentukan apakah urutan berisi elemen apa pun. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Menentukan apakah ada elemen dalam urutan atau elemen tersebut memenuhi kondisi. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Menghitung rata-rata dari urutan nilai numerik. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Menghitung rata-rata dari urutan nilai yang diperoleh dengan memanggil fungsi transformasi pada setiap elemen urutan masukan. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Mengubah tipe elemen ke tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Menggabungkan dua urutan. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Menentukan apakah urutan berisi nilai tertentu. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Mengembalikan jumlah elemen dalam urutan (dihitung melalui penghitung langsung). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan jumlah elemen dalam urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Mengembalikan elemen pada indeks tertentu dalam urutan. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Mengembalikan elemen pada indeks tertentu dalam urutan. |
| T [LINQ_First](../ienumerable/linq_first/)() | Mengembalikan elemen pertama dari urutan. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Mengembalikan elemen pertama dari urutan, atau nilai default jika urutan kosong. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi atau nilai default jika tidak ada elemen semacam itu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Mengelompokkan elemen-elemen dalam urutan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Mengelompokkan elemen-elemen dalam urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Mengembalikan elemen terakhir dari urutan. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Mengembalikan elemen terakhir dari urutan, atau nilai default jika urutan kosong. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Memanggil fungsi transformasi pada setiap elemen urutan generik dan mengembalikan nilai maksimum yang dihasilkan. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Memanggil fungsi transformasi pada setiap elemen urutan generik dan mengembalikan nilai minimum yang dihasilkan. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Menyaring elemen urutan berdasarkan tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen urutan dalam urutan menaik menurut nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen urutan dalam urutan menurun menurut nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Membalik urutan elemen dalam urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Mengubah elemen dalam urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Mengubah setiap elemen urutan menjadi bentuk baru dengan memasukkan indeks elemen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Memproyeksikan setiap elemen urutan dan menggabungkan urutan hasil menjadi satu urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Melewatkan sejumlah elemen berurutan yang ditentukan dari awal urutan dan mengembalikan sisanya. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Mengembalikan sejumlah elemen berurutan yang ditentukan dari awal urutan. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Membuat array dari urutan. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Membuat List<T> dari urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Menyaring urutan berdasarkan predikat yang ditentukan. |
|  [List](./list/)() | Membuat daftar kosong. |
|  [List](./list/)(int) | Membuat daftar dengan kapasitas yang telah ditentukan. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Konstruktor salin. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan penggandaan tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan menyalin konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan menyalin konstruktor subclass. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operator penugasan pindah. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operator penugasan pindah. |
| vector_t::reference [operator[]](./operator[]/)(int) | Fungsi akses. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Fungsi akses. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Mendapatkan iterator terbalik ke elemen terakhir koleksi (pertama dalam urutan terbalik). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Mendapatkan iterator terbalik ke elemen terakhir koleksi yang bersifat const (pertama dalam urutan terbalik). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| **bool** [Remove](./remove/)(const T\&) override | Menghapus instance pertama dari item tertentu dalam daftar. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Menghapus semua elemen yang cocok dengan predikat tertentu. |
| void [RemoveAt](./removeat/)(int) override | Menghapus item pada posisi yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [RemoveRange](./removerange/)(int, int) | Menghapus irisan daftar. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Mendapatkan iterator terbalik untuk elemen yang tidak ada sebelum awal koleksi. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Mendapatkan iterator terbalik untuk elemen yang tidak ada sebelum awal koleksi yang bersifat const. |
| void [Reverse](./reverse/)() | Membalik urutan elemen seluruh daftar. |
| void [Reverse](./reverse/)(int, int) | Membalik urutan elemen pada irisan daftar. |
| void [set_Capacity](./set_capacity/)(int) | Mengatur kapasitas daftar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Mengurutkan elemen dalam daftar. |
| void [Sort](./sort/)() | Mengurutkan elemen dalam daftar menggunakan pembanding default. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Mengurutkan elemen pada irisan daftar. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Mengurutkan elemen dalam daftar. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Mengonversi daftar menjadi array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| void [TrimExcess](./trimexcess/)() | Menyesuaikan kapasitas daftar dengan ukuran sebenarnya. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Menentukan apakah setiap elemen dalam koleksi memenuhi kondisi yang didefinisikan oleh predikat yang ditentukan. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mendapatkan implementasi iterator const begin untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mendapatkan implementasi iterator begin untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mendapatkan implementasi iterator const end untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Mendapatkan implementasi iterator end untuk kontainer saat ini. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [ValueType](./valuetype/) | Tipe ini. |
| [BaseType](./basetype/) | Tipe antarmuka. |
| [vector_t](./vector_t/) | Tipe data dasar. |
| [iterator](./iterator/) | Tipe iterator. |
| [const_iterator](./const_iterator/) | Tipe iterator const. |
| [reverse_iterator](./reverse_iterator/) | Tipe iterator terbalik. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipe iterator terbalik const. |
| [IEnumerablePtr](./ienumerableptr/) | Kontainer yang menampung elemen dengan tipe yang sama dengan yang kami pegang. |
| [IEnumeratorPtr](./ienumeratorptr/) | Tipe **Enumerator**. |

## Catatan

[List](./) - pembungkus di sekitar std::vector untuk digunakan dalam kode yang diterjemahkan. Memerlukan operator == diimplementasikan untuk tipe elemen. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan kesalahan runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Buat daftar pertama.
  auto list1 = MakeObject<List<int>>();

  // Isi daftar pertama.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Urutkan daftar pertama.
  // Item daftar pertama akan menjadi: {-5, 1, 3, 8}
  list1->Sort();

  // Hapus item pada indeks 2.
  // Item daftar pertama akan menjadi: {-5, 1, 8}
  list1->RemoveAt(2);

  // Sisipkan item ke indeks 1.
  // Item daftar pertama akan menjadi: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Buat daftar kedua.
  auto list2 = MakeObject<List<int>>();

  // Isi daftar kedua.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Tambahkan elemen dari daftar kedua ke daftar pertama.
  list1->AddRange(list2);

  // Cetak item daftar pertama.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
- 5 15 1 8 10 20 30
*/
```

## Lihat Juga

* Kelas [Object](../../system/object/)
* Kelas [IList](../ilist/)
* Ruang nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)