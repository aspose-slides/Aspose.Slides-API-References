---
title: Array
second_title: Referensi API Aspose.Slides untuk C++
description: "Kelas yang mewakili struktur data array. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeArray() dan System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 14
url: /id/system/array/
---
## Array kelas

Kelas yang merepresentasikan struktur data array. Objek dari kelas ini sebaiknya hanya dialokasikan menggunakan fungsi [System::MakeArray()](../makearray/) dan [System::MakeObject()](../makeobject/). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan error runtime dan/atau kegagalan assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen array |

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Add](./add/)(const T\&) override | Tidak didukung karena array yang direpresentasikan oleh objek saat ini bersifat read-only. |
|  [Array](./array/)() | Membuat array kosong. |
|  [Array](./array/)(int, const T\&) | Konstruktor pengisian. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Konstruktor pengisian. |
|  [Array](./array/)(int, const T) | Konstruktor pengisian. |
|  [Array](./array/)(**vector_t**\&&) | Konstruktor pemindahan. |
|  [Array](./array/)(const **vector_t**\&) | Konstruktor penyalinan. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Membuat objek [Array](./) dan mengisinya dengan nilai yang disalin dari objek std::vector yang tipe nilainya sama dengan **T** tetapi berbeda dari **UnderlyingType**. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Membuat objek [Array](./) dan mengisinya dengan nilai yang dipindahkan dari objek std::vector yang tipe nilainya sama dengan **T** tetapi berbeda dari **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Membuat objek [Array](./) dan mengisinya dengan nilai dari initializer list yang ditentukan berisi elemen berjenis **UnderlyingType**. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Membuat objek [Array](./) dan mengisinya dengan nilai dari array yang ditentukan berisi elemen berjenis **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Membuat objek [Array](./) dan mengisinya dengan nilai dari initializer list yang ditentukan berisi elemen berjenis bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Mengkasting array menjadi koleksi read-only. |
| [iterator](./iterator/) [begin](./begin/)() | Mengembalikan iterator ke elemen pertama dari kontainer. Jika kontainer kosong, iterator yang dikembalikan akan sama dengan [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Mengembalikan iterator ke elemen pertama dari kontainer yang bersifat const. Jika kontainer kosong, iterator yang dikembalikan akan sama dengan [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Melakukan pencarian biner pada array yang terurut. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | TIDAK DIIMPLEMENTASIKAN. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Mengembalikan iterator ke elemen pertama yang bersifat const pada kontainer. Jika kontainer kosong, iterator yang dikembalikan akan sama dengan [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Mengembalikan iterator ke elemen setelah elemen terakhir pada kontainer. Elemen ini berfungsi sebagai placeholder; mencoba mengaksesnya menghasilkan perilaku tak terdefinisi. |
| void [Clear](./clear/)() override | Tidak didukung karena array yang direpresentasikan oleh objek saat ini bersifat read-only. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Mengganti **count** nilai mulai dari indeks **startIndex** dalam array yang ditentukan dengan nilai default. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Mengkloning array. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Menyalin rentang elemen dari [System.Array](./) mulai dari sumber yang ditentukan. |
| **bool** [Contains](./contains/)(const T\&) const override | Menentukan apakah item yang ditentukan ada dalam array. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Membuat objek [Array](./) baru dan mengisinya dengan elemen array yang ditentukan yang dikonversi ke tipe **OutputType** menggunakan delegasi konverter yang ditentukan. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Membuat objek [Array](./) baru dan mengisinya dengan elemen array yang ditentukan yang dikonversi ke tipe **OutputType** menggunakan objek fungsi konverter yang ditentukan. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber ke array tujuan. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber ke array tujuan. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber ke tampilan array tujuan. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber ke tampilan array tujuan. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack ke array tujuan. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber ke array tujuan pada stack. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack ke array tujuan pada stack. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam tampilan array tujuan. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam tampilan array tujuan. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan pada stack. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan pada stack. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan pada stack. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Menyalin semua elemen array saat ini ke array tujuan yang ditentukan. Elemen dimasukkan ke dalam array tujuan mulai dari indeks yang ditentukan oleh argumen arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Menyalin semua elemen array saat ini ke array tujuan yang ditentukan. Elemen dimasukkan ke dalam array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Menyalin semua elemen array saat ini ke tampilan array tujuan yang ditentukan. Elemen dimasukkan ke dalam tampilan array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Menyalin sejumlah elemen yang ditentukan dari array saat ini mulai dari posisi yang ditentukan ke array tujuan yang ditentukan. Elemen dimasukkan ke dalam array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Menyalin sejumlah elemen yang ditentukan dari array saat ini mulai dari posisi yang ditentukan ke tampilan array tujuan yang ditentukan. Elemen dimasukkan ke dalam tampilan array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex. |
| int [Count](./count/)() const | Mengembalikan angka yang mewakili total jumlah semua elemen di semua dimensi array. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Mengembalikan iterator terbalik ke elemen pertama dari kontainer terbalik. Ini berkorespondensi dengan elemen terakhir dari kontainer non-terbalik. Jika kontainer kosong, iterator yang dikembalikan sama dengan [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Mengembalikan iterator terbalik ke elemen setelah elemen terakhir dari kontainer terbalik. Ini berkorespondensi dengan elemen sebelum elemen pertama dari kontainer non-terbalik. Elemen ini berfungsi sebagai placeholder; mencoba mengaksesnya menghasilkan perilaku tak terdefinisi. |
| **vector_t**\& [data](./data/)() | Mengembalikan referensi ke struktur data internal yang digunakan untuk menyimpan elemen array. |
| const **vector_t**\& [data](./data/)() const | Mengembalikan referensi konstan ke struktur data internal yang digunakan untuk menyimpan elemen array. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Mengembalikan pointer mentah ke awal buffer memori tempat elemen array disimpan. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Mengembalikan pointer mentah konstan ke awal buffer memori tempat elemen array disimpan. |
| [iterator](./iterator/) [end](./end/)() | Mengembalikan iterator ke elemen setelah elemen terakhir dari kontainer. Elemen ini berfungsi sebagai placeholder; mencoba mengaksesnya menghasilkan perilaku tak terdefinisi. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Mengembalikan iterator ke elemen setelah elemen terakhir dari kontainer yang bersifat const. Elemen ini berfungsi sebagai placeholder; mencoba mengaksesnya menghasilkan perilaku tak terdefinisi. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Menentukan apakah objek [Array](./) yang ditentukan berisi elemen yang memenuhi persyaratan predikat yang ditentukan. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Mencari elemen pertama dalam array yang ditentukan yang memenuhi kondisi predikat yang ditentukan. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Mengambil semua elemen yang sesuai dengan kondisi yang ditentukan oleh predikat yang ditentukan. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Mencari elemen pertama dalam array yang ditentukan yang memenuhi kondisi predikat yang ditentukan. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Melakukan aksi yang ditentukan pada setiap elemen dari array yang ditentukan. |
| int [get_Count](./get_count/)() const override | Mengembalikan ukuran array. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Memeriksa apakah koleksi memiliki ukuran tetap. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Menunjukkan apakah array bersifat read-only. |
| **int32_t** [get_Length](./get_length/)() const override | Mengembalikan integer 32-bit yang mewakili total jumlah semua elemen di semua dimensi array. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Mengembalikan integer 64-bit yang mewakili total jumlah semua elemen di semua dimensi array. |
| **int32_t** [get_Rank](./get_rank/)() const | TIDAK DIIMPLEMENTASIKAN. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Mendapatkan objek yang digunakan untuk menyinkronkan koleksi. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Mengembalikan pointer ke objek **Enumerator** yang menyediakan antarmuka IEnumerator untuk elemen array yang diwakili oleh objek saat ini. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../object/gethashcode/). Mengaktifkan hashing objek kustom. |
| int [GetLength](./getlength/)(int) | Mengembalikan jumlah elemen dalam dimensi yang ditentukan. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Mengembalikan jumlah elemen dalam dimensi yang ditentukan sebagai integer 64-bit. |
| int [GetLowerBound](./getlowerbound/)(int) const | Mengembalikan batas bawah dari dimensi yang ditentukan. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Mengembalikan variabel std::size_t yang mewakili total jumlah semua elemen di semua dimensi array. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari panggilan C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Mengembalikan batas atas dari dimensi yang ditentukan. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Konstruktor default. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Konstruktor salin. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Konstruktor pindah. |
| T [idx_get](./idx_get/)(int) const override | Mengembalikan item pada indeks yang ditentukan. |
| void [idx_set](./idx_set/)(int, T) override | Menetapkan nilai yang ditentukan sebagai item array pada indeks yang ditentukan. |
| int [IndexOf](./indexof/)(const T\&) const override | Menentukan indeks kemunculan pertama dari item yang ditentukan dalam array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Menentukan indeks kemunculan pertama dari item yang ditentukan dalam array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Menentukan indeks kemunculan pertama dari item yang ditentukan dalam array mulai dari indeks yang ditentukan. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Menentukan indeks kemunculan pertama dari item yang ditentukan dalam rentang item array yang ditentukan oleh indeks mulai dan jumlah elemen dalam rentang. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Mengisi array yang diwakili oleh objek saat ini dengan nilai-nilai dari array yang ditentukan. |
| void [Initialize](./initialize/)() | Mengisi array dengan objek tipe **T** yang dibangun secara default. |
| void [Insert](./insert/)(int, const T\&) override | Tidak didukung karena array yang diwakili oleh objek saat ini bersifat read-only. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Periksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Menentukan indeks kemunculan terakhir dari item yang ditentukan dalam rentang item array yang ditentukan oleh indeks mulai dan jumlah elemen dalam rentang. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Menentukan indeks kemunculan terakhir dari item yang ditentukan dalam array mulai dari indeks yang ditentukan. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Menentukan indeks kemunculan terakhir dari item yang ditentukan dalam array. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Menerapkan fungsi akumulator pada sebuah urutan. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Menentukan apakah semua elemen dalam urutan memenuhi kondisi. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Menentukan apakah sebuah urutan berisi elemen apa pun. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Menentukan apakah ada elemen dalam urutan atau elemen tersebut memenuhi suatu kondisi. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Menghitung rata-rata dari urutan nilai numerik. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Menghitung rata-rata dari urutan nilai yang diperoleh dengan memanggil fungsi transform pada setiap elemen dari urutan masukan. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Mengubah tipe elemen ke tipe yang ditentukan. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Menggabungkan dua urutan. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Menentukan apakah sebuah urutan berisi nilai yang ditentukan. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Mengembalikan jumlah elemen dalam urutan (dihitung melalui penghitung langsung). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Mengembalikan jumlah elemen dalam urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Mengembalikan elemen pada indeks yang ditentukan dalam urutan. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Mengembalikan elemen pada indeks yang ditentukan dalam urutan. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Mengembalikan elemen pertama dari urutan. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Mengembalikan elemen pertama dari urutan, atau nilai default jika urutan kosong. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi atau nilai default jika tidak ada elemen yang ditemukan. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Mengelompokkan elemen-elemen dari sebuah urutan. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Mengelompokkan elemen-elemen dari sebuah urutan. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Mengembalikan elemen terakhir dari urutan. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Mengembalikan elemen terakhir dari urutan, atau nilai default jika urutan kosong. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Memanggil fungsi transform pada setiap elemen dari urutan generik dan mengembalikan nilai maksimum yang dihasilkan. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Memanggil fungsi transform pada setiap elemen dari urutan generik dan mengembalikan nilai minimum yang dihasilkan. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Menyaring elemen-elemen dari urutan berdasarkan tipe yang ditentukan. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Mengurutkan elemen urutan secara naik berdasarkan nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Mengurutkan elemen urutan secara turun berdasarkan nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Membalik urutan elemen dalam urutan. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Mengubah elemen-elemen dari sebuah urutan. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Mengubah setiap elemen dari urutan menjadi bentuk baru dengan memasukkan indeks elemen. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Memproyeksikan setiap elemen dari urutan dan menggabungkan urutan hasil menjadi satu urutan. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Melewatkan sejumlah elemen berurutan yang ditentukan dari awal urutan dan mengembalikan sisanya. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Mengembalikan sejumlah elemen berurutan yang ditentukan dari awal urutan. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Membuat array dari sebuah urutan. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Membuat List<T> dari sebuah urutan. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Menyaring urutan berdasarkan predikat yang ditentukan. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Menemukan elemen terbesar dalam array menggunakan [operator<()](../operator_less/) untuk membandingkan elemen. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Menemukan elemen terkecil dalam array menggunakan [operator<()](../operator_less/) untuk membandingkan elemen. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operator penugasan pindah. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operator penugasan pindah. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Mengembalikan item pada indeks yang ditentukan. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Mengembalikan item pada indeks yang ditentukan. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Mengembalikan pointer ke elemen pertama dari array satu dimensi. Untuk array multi-dimensi hasil tidak terdefinisi. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Mengembalikan iterator terbalik ke elemen pertama dari kontainer terbalik. Itu berkorespondensi dengan elemen terakhir dari kontainer tidak terbalik. Jika kontainer kosong, iterator yang dikembalikan sama dengan [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Mengembalikan iterator terbalik ke elemen pertama dari kontainer terbalik. Ini berkorespondensi dengan elemen terakhir dari kontainer yang tidak terbalik. Jika kontainer kosong, iterator yang dikembalikan sama dengan [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan objek tipe nilai dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| **bool** [Remove](./remove/)(const T\&) override | Tidak didukung karena array yang diwakili oleh objek saat ini bersifat hanya-baca. |
| void [RemoveAt](./removeat/)(int) override | Tidak didukung karena array yang diwakili oleh objek saat ini bersifat hanya-baca. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Mengembalikan iterator terbalik ke elemen yang berada setelah elemen terakhir dari kontainer terbalik. Ini berkorespondensi dengan elemen yang berada sebelum elemen pertama dari kontainer yang tidak terbalik. Elemen ini berfungsi sebagai placeholder, mencoba mengaksesnya mengakibatkan perilaku tak terdefinisi. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Mengembalikan iterator terbalik ke elemen yang berada setelah elemen terakhir dari kontainer terbalik. Ini berkorespondensi dengan elemen yang berada sebelum elemen pertama dari kontainer yang tidak terbalik. Elemen ini berfungsi sebagai placeholder, mencoba mengaksesnya mengakibatkan perilaku tak terdefinisi. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Mengubah ukuran array yang ditentukan ke nilai yang ditentukan atau membuat array baru dengan ukuran yang ditentukan. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Membalik urutan elemen dalam array yang ditentukan. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Membalik urutan rentang elemen dalam array yang ditentukan. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Membuat array memperlakukan pointer yang disimpan sebagai lemah (jika berlaku). |
| void [SetValue](./setvalue/)(const T\&, int) | Menetapkan nilai elemen pada indeks yang ditentukan. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Mengurutkan elemen dalam array yang ditentukan menggunakan pembanding default. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Mengurutkan rentang elemen dalam array yang ditentukan menggunakan pembanding default. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Mengurutkan elemen dalam array yang ditentukan menggunakan pembanding yang ditentukan. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | TIDAK DIIMPLEMENTASIKAN. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Mengurutkan elemen dalam array yang ditentukan menggunakan perbandingan yang ditentukan. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Mengurutkan dua array, satu berisi kunci dan yang lainnya berisi item yang bersesuaian, berdasarkan nilai array yang berisi kunci, elemen-elemennya dibandingkan menggunakan operator<. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Mengurutkan dua array, satu berisi kunci dan yang lainnya berisi item yang bersesuaian, berdasarkan nilai array yang berisi kunci, elemen-elemennya dibandingkan menggunakan pembanding default. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog dari metode C# [Object.ToString()](../object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Menentukan apakah semua elemen dalam array yang ditentukan memenuhi kondisi yang didefinisikan oleh predikat yang diberikan. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Menerapkan konstruk C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Menerapkan pernyataan unlock C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mendapatkan implementasi iterator const begin untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mendapatkan implementasi iterator begin untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mendapatkan implementasi iterator const end untuk kontainer saat ini. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Mendapatkan implementasi iterator end untuk kontainer saat ini. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [ValueType](./valuetype/) | Alias untuk tipe elemen array. |
| [UnderlyingType](./underlyingtype/) | Alias untuk tipe yang digunakan merepresentasikan setiap elemen array. |
| [EnumerablePtr](./enumerableptr/) | Alias untuk tipe shared pointer yang menunjuk ke objek IEnumerable yang berisi elemen bertipe **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Alias untuk tipe shared pointer yang menunjuk ke objek IEnumerator yang berisi elemen bertipe **T**. |
| [iterator](./iterator/) | Tipe iterator. |
| [const_iterator](./const_iterator/) | Tipe iterator const. |
| [reverse_iterator](./reverse_iterator/) | Tipe iterator terbalik. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipe iterator terbalik const. |

## Catatan

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Membuat dan mengisi array.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Mencetak elemen array.
  Print(arrayPtr);

  // Mengurutkan elemen array secara naik.
  Array<int32_t>::Sort(arrayPtr);

  // Mencetak elemen array.
  Print(arrayPtr);

  // Mencetak jumlah elemen array.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Mencetak indeks elemen yang bernilai 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Mengubah ukuran array.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Mencetak elemen array.
  Print(arrayPtr);

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Lihat Juga

* Kelas [ArrayBase](../arraybase/)
* Kelas [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)