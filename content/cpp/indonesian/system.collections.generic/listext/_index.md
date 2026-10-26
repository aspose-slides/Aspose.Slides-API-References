---
title: ListExt
second_title: Referensi API Aspose.Slides untuk C++
description: kelas List generik yang mengimplementasikan antarmuka IListWrapper
type: docs
weight: 443
url: /id/system.collections.generic/listext/
---
## ListExt kelas

generic [List](../list/) kelas yang mengimplementasikan antarmuka [IListWrapper](../../system.collections/ilistwrapper/)

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [_add_range](../list/_add_range/)(std:: initializer_list\<T\>) | Spesifik C++. |
| void [Add](../list/add/)(const T\&) override | Menambahkan elemen ke akhir daftar. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Menambahkan elemen ke daftar; digunakan saat menerjemahkan initializer. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Menambahkan semua elemen dari koleksi (atau dirinya sendiri) ke akhir daftar saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Mendapatkan referensi read-only ke koleksi ini. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Mendapatkan iterator ke elemen pertama koleksi. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Mendapatkan iterator ke elemen pertama koleksi yang const-qualified. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Mencari item dalam daftar terurut. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Mencari item dalam daftar terurut. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Mencari item dalam daftar terurut. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Mendapatkan iterator ke elemen pertama yang const-qualified dari koleksi. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Mendapatkan iterator untuk elemen const-qualified yang tidak ada di belakang akhir koleksi. |
| void [Clear](../list/clear/)() override | Menghapus semua elemen. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Memeriksa apakah item ada dalam daftar. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Membuat daftar elemen yang dikonversi ke tipe yang berbeda. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Menyalin elemen daftar ke elemen array yang ada. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Menyalin semua elemen ke elemen array yang ada. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Menyalin elemen mulai dari indeks yang ditentukan ke elemen array yang ada. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Mendapatkan iterator terbalik ke elemen const-qualified terakhir dari koleksi (pertama dalam urutan terbalik). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) implementasi antarmuka. |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) helper implementasi untuk tipe referensi. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) helper implementasi untuk tipe nilai. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) helper implementasi untuk tipe lain. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Mendapatkan iterator terbalik untuk elemen const-qualified yang tidak ada sebelum awal koleksi. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Fungsi akses struktur data dasar. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Fungsi akses struktur data dasar. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Mendapatkan iterator untuk elemen yang tidak ada di belakang akhir koleksi. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Mendapatkan iterator untuk elemen yang tidak ada di belakang akhir koleksi yang const-qualified. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Memeriksa apakah elemen yang memenuhi predikat tertentu ada dalam daftar. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen yang memenuhi predikat tertentu. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Mencari elemen terakhir yang memenuhi predikat tertentu. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Menerapkan aksi ke semua elemen dalam daftar. |
| int [get_Capacity](../list/get_capacity/)() const | Mendapatkan kapasitas daftar saat ini. |
| int [get_Count](../list/get_count/)() const override | Mendapatkan jumlah elemen dalam daftar saat ini. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Memeriksa apakah koleksi berukuran tetap. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Memeriksa apakah koleksi hanya-baca. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Mendapatkan objek yang digunakan untuk sinkronisasi koleksi. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Mendapatkan enumerator untuk mengiterasi elemen daftar. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Membuat iris (slice) daftar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Konstruktor default. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Konstruktor salin. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Konstruktor pindah. |
| T [idx_get](../list/idx_get/)(int) const override | Mendapatkan elemen pada posisi tertentu. |
| void [idx_set](../list/idx_set/)(int, T) override | Mengatur elemen pada posisi tertentu. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Mendapatkan indeks pertama dari item tertentu. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Mencari item tertentu dalam daftar. |
| void [Insert](../list/insert/)(int, const T\&) override | Menyisipkan item pada posisi yang ditentukan. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Menyisipkan rentang data pada posisi tertentu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam seluruh daftar. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam rentang elemen di [List](../list/) yang dimulai dari elemen pertama hingga indeks yang ditentukan. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam rentang elemen di [List](../list/) yang berisi jumlah elemen yang ditentukan dan berakhir pada indeks yang ditentukan. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Menerapkan fungsi akumulator pada urutan. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Menentukan apakah semua elemen dalam urutan memenuhi kondisi. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Menentukan apakah urutan berisi elemen apa pun. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Menentukan apakah ada elemen dalam urutan yang ada atau memenuhi kondisi. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Menghitung rata-rata dari urutan nilai numerik. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Menghitung rata-rata dari urutan nilai yang diperoleh dengan memanggil fungsi transformasi pada setiap elemen urutan masukan. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Mencasting elemen ke tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Menggabungkan dua urutan. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Menentukan apakah urutan berisi nilai tertentu. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Mengembalikan jumlah elemen dalam urutan (dihitung melalui penghitung langsung). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan jumlah elemen dalam urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Mengembalikan elemen pada indeks tertentu dalam urutan. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Mengembalikan elemen pada indeks tertentu dalam urutan. |
| T [LINQ_First](../ienumerable/linq_first/)() | Mengembalikan elemen pertama dalam urutan. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan elemen pertama dalam urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Mengembalikan elemen pertama dalam urutan, atau nilai default jika urutan kosong. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Mengembalikan elemen pertama dalam urutan yang memenuhi kondisi atau nilai default jika tidak ditemukan elemen tersebut. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Mengelompokkan elemen dalam urutan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Mengelompokkan elemen dalam urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Mengembalikan elemen terakhir dalam urutan. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Mengembalikan elemen terakhir dalam urutan, atau nilai default jika urutan kosong. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Memanggil fungsi transformasi pada setiap elemen urutan generik dan mengembalikan nilai maksimum yang dihasilkan. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Memanggil fungsi transformasi pada setiap elemen urutan generik dan mengembalikan nilai minimum yang dihasilkan. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Menyaring elemen urutan berdasarkan tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen urutan secara naik berdasarkan nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen urutan secara menurun berdasarkan nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Membalik urutan elemen dalam urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Mengubah elemen urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Mengubah setiap elemen urutan menjadi bentuk baru dengan memasukkan indeks elemen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Menyajikan setiap elemen urutan dan menggabungkan urutan hasil menjadi satu urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Melewatkan sejumlah elemen berurutan yang ditentukan dari awal urutan dan mengembalikan sisanya. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Mengembalikan sejumlah elemen berurutan yang ditentukan dari awal urutan. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Membuat array dari urutan. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Membuat List<T> dari urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Menyaring urutan berdasarkan predikat yang ditentukan. |
|  [List](../list/list/)() | Membuat daftar kosong. |
|  [List](../list/list/)(int) | Membuat daftar dengan kapasitas yang telah ditentukan. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Konstruktor salin. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apapun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apapun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operator penugasan pindah. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operator penugasan pindah. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Fungsi accessor. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Fungsi accessor. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Mendapatkan iterator terbalik ke elemen terakhir koleksi (pertama dalam urutan terbalik). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Mendapatkan iterator terbalik ke elemen terakhir koleksi yang const-qualified (pertama dalam urutan terbalik). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| **bool** [Remove](../list/remove/)(const T\&) override | Menghapus instansi pertama dari item tertentu dalam daftar. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Menghapus semua elemen yang cocok dengan predikat tertentu. |
| void [RemoveAt](../list/removeat/)(int) override | Menghapus item pada posisi yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [RemoveRange](../list/removerange/)(int, int) | Menghapus irisan daftar. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Mendapatkan iterator terbalik untuk elemen yang tidak ada sebelum awal koleksi. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Mendapatkan iterator terbalik untuk elemen yang tidak ada sebelum awal koleksi yang const-qualified. |
| void [Reverse](../list/reverse/)() | Membalik urutan elemen seluruh daftar. |
| void [Reverse](../list/reverse/)(int, int) | Membalik urutan elemen irisan daftar. |
| void [set_Capacity](../list/set_capacity/)(int) | Mengatur kapasitas daftar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n sebagai weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Mengurutkan elemen dalam daftar. |
| void [Sort](../list/sort/)() | Mengurutkan elemen dalam daftar menggunakan pembanding default. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Mengurutkan elemen dalam irisan daftar. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Mengurutkan elemen dalam daftar. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Mengonversi daftar menjadi array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom menjadi string. |
| void [TrimExcess](../list/trimexcess/)() | Mengatur kapasitas daftar agar sesuai dengan ukuran. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Menentukan apakah setiap elemen dalam koleksi memenuhi kondisi yang didefinisikan oleh predikat yang ditentukan. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Mendapatkan implementasi iterator const begin untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Mendapatkan implementasi iterator begin untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Mendapatkan implementasi iterator const end untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Mendapatkan implementasi iterator end untuk kontainer saat ini. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## Lihat Juga

* Kelas [List](../list/)
* Kelas [IListWrapper](../../system.collections/ilistwrapper/)
* Ruang Nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)