---
title: Array
second_title: Aspose.Slides for C++ API Referansı
description: "Sınıf, bir dizi veri yapısını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeArray() ve System::MakeObject() fonksiyonlarıyla ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da new operatörüyle asla oluşturmamalısınız; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr göstergesine sarmalayıp, bu göstergeyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 14
url: /tr/system/array/
---
## Dizi sınıfı

Dizi veri yapısını temsil eden sınıf. Bu sınıfın nesneleri yalnızca [System::MakeArray()](../makearray/) ve [System::MakeObject()](../makeobject/) işlevleri kullanılarak tahsis edilmelidir. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Bir dizinin elemanlarının tipi |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Add](./add/)(const T\&) override | Desteklenmez çünkü mevcut nesne tarafından temsil edilen dizi yalnızca okuma kipindedir. |
| [Array](./array/)() | Boş bir dizi oluşturur. |
| [Array](./array/)(int, const T\&) | Doldurma kurucusu. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Doldurma kurucusu. |
| [Array](./array/)(int, const T) | Doldurma kurucusu. |
| [Array](./array/)(**vector_t**\&&) | Taşıma kurucusu. |
| [Array](./array/)(const **vector_t**\&) | Kopyalama kurucusu. |
| [Array](./array/)(const std::vector\<Q\>\&) | Bir [Array](./) nesnesi oluşturur ve **T** ile aynı tipe sahip ancak **UnderlyingType**'dan farklı bir std::vector nesnesinden kopyalanmış değerlerle doldurur. |
| [Array](./array/)(std::vector\<Q\>\&&) | Bir [Array](./) nesnesi oluşturur ve **T** ile aynı tipe sahip ancak **UnderlyingType**'dan farklı bir std::vector nesnesinden taşınmış değerlerle doldurur. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Bir [Array](./) nesnesi oluşturur ve **UnderlyingType** tipinde öğeler içeren belirtilen başlatıcı listesindeki değerlerle doldurur. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Bir [Array](./) nesnesi oluşturur ve **UnderlyingType** tipinde öğeler içeren belirtilen diziden değerlerle doldurur. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | Bir [Array](./) nesnesi oluşturur ve bool tipinde öğeler içeren belirtilen başlatıcı listesindeki değerlerle doldurur. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Diziyi yalnızca okuma koleksiyonuna dönüştürür. |
| [iterator](./iterator/) [begin](./begin/)() | Kapsayıcının ilk öğesine bir yineleyici döndürür. Kapsayıcı boşsa, döndürülen yineleyici [end()](./end/) değerine eşit olur. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Const-nitelikli kapsayıcının ilk öğesine bir yineleyici döndürür. Kapsayıcı boşsa, döndürülen yineleyici [end()](./end/) değerine eşit olur. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Sıralı dizide ikili arama gerçekleştirir. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NOT IMPLEMENTED. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Kapsayıcının ilk const-nitelikli öğesine bir yineleyici döndürür. Kapsayıcı boşsa, döndürülen yineleyici [cend()](./cend/) değerine eşit olur. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Kapsayıcının son öğesini izleyen öğeye bir yineleyici döndürür. Bu öğe bir tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| void [Clear](./clear/)() override | Desteklenmez çünkü mevcut nesne tarafından temsil edilen dizi yalnızca okuma kipindedir. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Belirtilen dizide **startIndex** konumundan başlayarak **count** değerini varsayılan değerlerle değiştirir. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Diziyi klonlar. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Belirtilen kaynaktan başlayan bir [System.Array](./) aralığındaki öğeleri kopyalar. |
| **bool** [Contains](./contains/)(const T\&) const override | Belirtilen öğenin dizi içinde olup olmadığını belirler. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Yeni bir [Array](./) nesnesi oluşturur ve belirtilen dönüştürücü temsilcisi kullanılarak **OutputType** tipine dönüştürülmüş belirtilen dizinin öğeleriyle doldurur. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Yeni bir [Array](./) nesnesi oluşturur ve belirtilen dönüştürücü işlev nesnesi kullanılarak **OutputType** tipine dönüştürülmüş belirtilen dizinin öğeleriyle doldurur. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kaynak diziden hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kaynak dizi görünümünden hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Kaynak diziden hedef dizi görünümüne belirtilen sayıda öğeyi kopyalar. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Kaynak dizi görünümünden hedef dizi görünümüne belirtilen sayıda öğeyi kopyalar. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Yığıttaki kaynak diziden hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Kaynak diziden yığıttaki hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Yığıttaki kaynak diziden yığıttaki hedef diziye belirtilen sayıda öğeyi kopyalar. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kaynak diziden belirtilen indeksten başlayarak belirli sayıda öğeyi hedef dizideki belirtilen konuma kopyalar. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kaynak dizi görünümünden belirtilen indeksten başlayarak belirli sayıda öğeyi hedef dizideki belirtilen konuma kopyalar. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kaynak diziden belirtilen indeksten başlayarak belirli sayıda öğeyi hedef dizi görünümündeki belirtilen konuma kopyalar. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kaynak dizi görünümünden belirtilen indeksten başlayarak belirli sayıda öğeyi hedef dizi görünümündeki belirtilen konuma kopyalar. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Yığıttaki kaynak diziden belirtilen indeksten başlayarak belirli sayıda öğeyi hedef dizideki belirtilen konuma kopyalar. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Kaynak diziden belirtilen indeksten başlayarak belirli sayıda öğeyi yığıttaki hedef dizideki belirtilen konuma kopyalar. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Yığıttaki kaynak diziden belirtilen indeksten başlayarak belirli sayıda öğeyi yığıttaki hedef dizideki belirtilen konuma kopyalar. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kaynak dizi görünümünden belirtilen indeksten başlayarak belirli sayıda öğeyi yığıttaki hedef dizideki belirtilen konuma kopyalar. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Mevcut dizinin tüm öğelerini belirtilen hedef diziye kopyalar. Öğeler, diziİndeksi bağımsız değişkeniyle belirtilen indeksten itibaren hedef diziye eklenir. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Mevcut dizinin tüm öğelerini belirtilen hedef diziye kopyalar. Öğeler, dstİndex bağımsız değişkeniyle belirtilen indeksten itibaren hedef diziye eklenir. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Mevcut dizinin tüm öğelerini belirtilen hedef dizi görünümüne kopyalar. Öğeler, dstİndex bağımsız değişkeniyle belirtilen indeksten itibaren hedef dizi görünümüne eklenir. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Mevcut dizinin belirtilen konumundan başlayarak belirli sayıda öğeyi belirtilen hedef diziye kopyalar. Öğeler, dstİndex bağımsız değişkeniyle belirtilen indeksten itibaren hedef diziye eklenir. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Mevcut dizinin belirtilen konumundan başlayarak belirli sayıda öğeyi belirtilen hedef dizi görünümüne kopyalar. Öğeler, dstİndex bağımsız değişkeniyle belirtilen indeksten itibaren hedef dizi görünümüne eklenir. |
| int [Count](./count/)() const | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden bir sayı döndürür. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Tersleştirilmiş kapsayıcının ilk öğesine bir ters yineleyici döndürür. Bu, tersleştirilmemiş kapsayıcının son öğesine karşılık gelir. Kapsayıcı boşsa, döndürülen yineleyici [crend()](./crend/) değerine eşit olur. |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Tersleştirilmiş kapsayıcının son öğesini izleyen öğeye bir ters yineleyici döndürür. Bu, tersleştirilmemiş kapsayıcının ilk öğesinden önceki öğeye karşılık gelir. Bu öğe bir tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| **vector_t**\& [data](./data/)() | Dizinin öğelerini depolamak için kullanılan iç veri yapısına bir referans döndürür. |
| const **vector_t**\& [data](./data/)() const | Dizinin öğelerini depolamak için kullanılan iç veri yapısına sabit bir referans döndürür. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Dizi öğelerinin depolandığı bellek tamponunun başlangıcına saf bir işaretçi döndürür. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Dizi öğelerinin depolandığı bellek tamponunun başlangıcına sabit bir saf işaretçi döndürür. |
| [iterator](./iterator/) [end](./end/)() | Kapsayıcının son öğesini izleyen öğeye bir yineleyici döndürür. Bu öğe bir tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Const-nitelikli kapsayıcının son öğesini izleyen öğeye bir yineleyici döndürür. Bu öğe bir tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa yol açar. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Nesneleri C# [Object.Equals](../object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri, IEC 60559:1989 standardına göre NaN hiçbir değere eşit değildir, NaN dahil, aynı olsa bile eşit kabul edilir. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# stilinde bir kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Belirtilen [Array](./) nesnesinin, belirtilen koşulu sağlayan bir öğe içerip içermediğini belirler. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Belirtilen dizide, belirtilen koşulun şartlarını sağlayan ilk öğeyi arar. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Belirtilen koşul tarafından tanımlanan şartları karşılayan tüm öğeleri alır. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Belirtilen dizide, belirtilen koşulun şartlarını sağlayan ilk öğeyi arar. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Belirtilen dizideki her öğe üzerinde belirtilen eylemi gerçekleştirir. |
| int [get_Count](./get_count/)() const override | Dizinin boyutunu döndürür. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Koleksiyonun sabit boyutta olup olmadığını denetler. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Dizinin sadece okunur olup olmadığını gösterir. |
| **int32_t** [get_Length](./get_length/)() const override | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden 32-bit tamsayıyı döndürür. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden 64-bit tamsayıyı döndürür. |
| **int32_t** [get_Rank](./get_rank/)() const | IMPLEMENTED DEĞİL. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayıcı veri yapısını alır. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Geçerli nesne tarafından temsil edilen dizinin öğelerine IEnumerator arayüzü sağlayan **Enumerator** nesnesine bir işaretçi döndürür. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun benzeri. Özelleştirilmiş nesnelerin hashlenmesini sağlar. |
| int [GetLength](./getlength/)(int) | Belirtilen boyuttaki öğe sayısını döndürür. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Belirtilen boyuttaki öğe sayısını 64-bit tamsayı olarak döndürür. |
| int [GetLowerBound](./getlowerbound/)(int) const | Belirtilen boyutun alt sınırını döndürür. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Dizinin tüm boyutlarındaki tüm öğelerin toplam sayısını temsil eden bir std::size_t değişkeni döndürür. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının benzeri. |
| int [GetUpperBound](./getupperbound/)(int) | Belirtilen boyutun üst sınırını döndürür. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Varsayılan kurucu. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Kopya kurucu. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Taşıma kurucu. |
| T [idx_get](./idx_get/)(int) const override | Belirtilen dizindeki öğeyi döndürür. |
| void [idx_set](./idx_set/)(int, T) override | Belirtilen değeri, dizinin belirtilen indeksindeki öğe olarak ayarlar. |
| int [IndexOf](./indexof/)(const T\&) const override | Dizide belirtilen öğenin ilk göründüğü konumun indeksini belirler. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Dizide belirtilen öğenin ilk göründüğü konumun indeksini belirler. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Belirtilen indeksden başlayarak dizide belirtilen öğenin ilk göründüğü konumun indeksini belirler. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Başlangıç indeksi ve aralıktaki öğe sayısı ile belirtilen dizi aralığında belirtilen öğenin ilk göründüğü konumun indeksini belirler. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Geçerli nesne tarafından temsil edilen diziyi, belirtilen diziden gelen değerlerle doldurur. |
| void [Initialize](./initialize/)() | Diziyi **T** tipinin varsayılan olarak oluşturulmuş nesneleriyle doldurur. |
| void [Insert](./insert/)(int, const T\&) override | Desteklenmez çünkü geçerli nesne tarafından temsil edilen dizi sadece okunur. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Başlangıç indeksi ve aralıktaki öğe sayısı ile belirtilen dizi aralığında belirtilen öğenin son göründüğü konumun indeksini belirler. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Belirtilen indeksten başlayarak dizide belirtilen öğenin son göründüğü konumun indeksini belirler. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Dizide belirtilen öğenin son göründüğü konumun indeksini belirler. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Bir dizi üzerinde bir toplayıcı fonksiyon uygular. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm öğelerin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizideki herhangi bir öğenin var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Sayısal değerler dizisinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Girdi dizisinin her öğesi üzerinde bir dönüştürme fonksiyonu çağırılarak elde edilen değerler dizisinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Öğeleri belirtilen türe dönüştürür. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bir dizinin belirtilen bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Dizideki öğe sayısını (doğrudan sayım yoluyla) döndürür. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan bir dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini, dizi boşsa varsayılan bir değerle birlikte döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Koşulu sağlayan dizinin ilk öğesini veya böyle bir öğe bulunamazsa varsayılan değeri döndürür. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Bir dizi öğelerini gruplayarak. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Bir dizi öğelerini gruplayarak. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini, dizi boşsa varsayılan değerle birlikte döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Genel bir dizideki her öğe üzerinde bir dönüştürme fonksiyonu çağırır ve elde edilen en büyük değeri döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Genel bir dizideki her öğe üzerinde bir dönüştürme fonksiyonu çağırır ve elde edilen en küçük değeri döndürür. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Dizinin öğelerini belirtilen türe göre filtreler. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Anahtar seçicisi tarafından seçilen anahtar değerlerine göre bir dizinin öğelerini artan sırada sıralar. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Anahtar seçicisi tarafından seçilen anahtar değerlerine göre bir dizinin öğelerini azalan sırada sıralar. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Bir dizideki öğelerin sırasını tersine çevirir. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Bir dizinin öğelerini dönüştürür. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her öğesini, öğenin indeksini ekleyerek yeni bir forma dönüştürür. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her öğesini projekte eder ve ortaya çıkan dizileri tek bir dizi içinde birleştirir. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başından belirli sayıda ardışık öğeyi atlar ve geri kalanını döndürür. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Bir dizinin başından belirli sayıda ardışık öğeyi döndürür. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Bir diziden bir dizi oluşturur. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Bir diziden bir List<T> oluşturur. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Bir diziyi belirtilen koşula göre filtreler. |
| void [Lock](../object/lock/)() | C# lock() ifadesi kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözlemci nesnesini kullanın. |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | [operator<()](../operator_less/) kullanarak dizideki en büyük öğeyi bulur. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun benzeri. Özelleştirilmiş tiplerin kopyalanmasını sağlar. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | [operator<()](../operator_less/) kullanarak dizideki en küçük öğeyi bulur. |
|  [Object](../object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya kurucu. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya kurucu ile oluşturulmasını sağlar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya kurucu ile oluşturulmasını sağlar. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Taşıma atama operatörü. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) |  |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Belirtilen dizindeki öğeyi döndürür. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Belirtilen dizindeki öğeyi döndürür. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Tek boyutlu bir dizinin ilk öğesine işaretçi döndürür. Çok boyutlu dizilerde sonuç tanımsızdır. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Ters çevrilmiş konteynerin ilk öğesine bir ters iteratör döndürür. Bu, ters çevrilmemiş konteynerin son öğesine karşılık gelir. Konteyner boşsa, döndürülen iteratör [rend()](./rend/) ile eşittir. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Tersine çevrilmiş konteynerin ilk elemanına bir ters yineleyici döndürür. Bu, tersine çevrilmemiş konteynerin son elemanına karşılık gelir. Konteyner boşsa, döndürülen yineleyici [rend()](./rend/) ile eşittir. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin string durumu için özelleştirmesi. |
| **bool** [Remove](./remove/)(const T\&) override | Desteklenmez çünkü mevcut nesne tarafından temsil edilen dizi yalnızca okunabilir. |
| void [RemoveAt](./removeat/)(int) override | Desteklenmez çünkü mevcut nesne tarafından temsil edilen dizi yalnızca okunabilir. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Tersine çevrilmiş konteynerin son elemanını izleyen elemana bir ters yineleyici döndürür. Bu, tersine çevrilmemiş konteynerin ilk elemanından önceki elemana karşılık gelir. Bu öğe bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa neden olur. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Tersine çevrilmiş konteynerin son elemanını izleyen elemana bir ters yineleyici döndürür. Bu, tersine çevrilmemiş konteynerin ilk elemanından önceki elemana karşılık gelir. Bu öğe bir yer tutucu görevi görür; ona erişmeye çalışmak tanımsız davranışa neden olur. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Belirtilen dizinin boyutunu belirtilen değere değiştirir veya belirtilen boyutta yeni bir dizi oluşturur. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Belirtilen dizideki elemanları tersine çevirir. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Belirtilen dizideki bir eleman aralığını tersine çevirir. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Dizinin saklanan işaretçileri zayıf olarak ele almasını sağlar (uygulanabilir ise). |
| void [SetValue](./setvalue/)(const T\&, int) | Belirtilen indeksteki elemanın değerini ayarlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Belirtilen dizideki elemanları varsayılan karşılaştırıcı ile sıralar. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Belirtilen dizideki bir aralık elemanları varsayılan karşılaştırıcı ile sıralar. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Belirtilen dizideki elemanları belirtilen karşılaştırıcı ile sıralar. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | UYGULANMAMIŞTIR. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Belirtilen dizideki elemanları belirtilen karşılaştırma ile sıralar. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Birinde anahtarlar, diğerinde karşılık gelen öğeler bulunan iki diziyi, anahtar dizisinin değerlerine göre, elemanların operator< kullanılarak karşılaştırıldığı şekilde sıralar. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Birinde anahtarlar, diğerinde karşılık gelen öğeler bulunan iki diziyi, anahtar dizisinin değerlerine göre, elemanların varsayılan karşılaştırıcı ile karşılaştırıldığı şekilde sıralar. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | [Object.ToString()](../object/tostring/) metodunun C# analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Belirtilen dizideki tüm elemanların belirtilen koşulu sağlayıp sağlamadığını belirler. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözcü nesnesini kullanın. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut konteyner için başlangıç const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut konteyner için başlangıç yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut konteyner için son const yineleyicisinin uygulamasını alır. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut konteyner için son yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Yıkıcı. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımları

| TipTanım | Açıklama |
| --- | --- |
| [ValueType](./valuetype/) | Dizinin eleman tipinin bir takma adıdır. |
| [UnderlyingType](./underlyingtype/) | Dizinin her bir elemanını temsil etmek için kullanılan tipin bir takma adıdır. |
| [EnumerablePtr](./enumerableptr/) | **T** tipindeki elemanları içeren IEnumerable nesnesine işaret eden paylaşımlı gösterici tipinin bir takma adı. |
| [EnumeratorPtr](./enumeratorptr/) | **T** tipindeki elemanları içeren IEnumerator nesnesine işaret eden paylaşımlı gösterici tipinin bir takma adı. |
| [iterator](./iterator/) | Yineleyici tipi. |
| [const_iterator](./const_iterator/) | Const yineleyici tipi. |
| [reverse_iterator](./reverse_iterator/) | Tersine yineleyici tipi. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const tersine yineleyici tipi. |

## Açıklamalar



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
  // Dizi oluştur ve doldur.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Dizi öğelerini yazdır.
  Print(arrayPtr);

  // Dizi öğelerini artan sırada sırala.
  Array<int32_t>::Sort(arrayPtr);

  // Dizi öğelerini yazdır.
  Print(arrayPtr);

  // Dizi öğelerinin sayısını yazdır.
  std::cout << arrayPtr->get_Length() << std::endl;

  // 4'e eşit olan öğenin indeksini yazdır.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Dizinin boyutunu değiştir.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Dizi öğelerini yazdır.
  Print(arrayPtr);

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Diğer

* Sınıf [ArrayBase](../arraybase/)
* Sınıf [IList](../../system.collections.generic/ilist/)
* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)