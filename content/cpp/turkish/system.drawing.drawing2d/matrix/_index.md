---
title: Matrix
second_title: Aspose.Slides for C++ API Referansı
description: "Dönüşüm işlemlerini tanımlayan 3x3 bir matris temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığına (stack) ya da new operatörüyle oluşturmaya çalışmayın, çünkü çalışma zamanı hatalarına ve/veya koşul (assert) hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 118
url: /tr/system.drawing.drawing2d/matrix/
---
## Matrix sınıfı

Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Geçerli nesnenin bir kopyasını oluşturur. |
| void [Dispose](./dispose/)() | Geçerli nesne tarafından edinilen tüm işletim sistemi kaynaklarını serbest bırakır. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Belirtilen nesnenin bir [Matrix](./) olup olmadığını ve bu nesneyle aynı olup olmadığını test eder. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Matris elemanlarını aşağıdaki sırada içeren bir dizi döndürür: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Geçerli nesne tarafından temsil edilen matrisin birim matris olup olmadığını belirler. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Geçerli nesne tarafından temsil edilen matrisin terslenebilir olup olmadığını belirler. |
| **float** [get_OffsetX](./get_offsetx/)() const | Geçerli nesne tarafından temsil edilen matrisin X çeviri değerini döndürür. |
| **float** [get_OffsetY](./get_offsety/)() const | Geçerli nesne tarafından temsil edilen matrisin Y çeviri değerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| void [Invert](./invert/)() | Geçerli nesne tarafından temsil edilen matrisi tersine çevirir. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| [Matrix](./matrix/)() | [Matrix](./) sınıfının bir birim matris temsil eden yeni bir örneğini oluşturur. |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | [Matrix](./) sınıfının yeni bir örneğini oluşturur ve belirtilen değerlerle başlatır. |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüm için [Matrix](./) sınıfının yeni bir örneğini oluşturur. |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüm için [Matrix](./) sınıfının yeni bir örneğini oluşturur. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özelleştirilmiş tiplerin kopyalanmasını sağlar. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Geçerli nesne tarafından temsil edilen matrisi belirtilen matrisle çarpar. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Geçerli nesne tarafından temsil edilen matrisi belirtilen matrisle çarpar. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapıları başlatılır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [Reset](./reset/)() | Geçerli nesne tarafından temsil edilen matrisi birim matris olacak şekilde sıfırlar. |
| void [Rotate](./rotate/)(**float**) | Geçerli nesne tarafından temsil edilen matrisi belirtilen açı kadar saat yönünde döndürür. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Geçerli nesne tarafından temsil edilen matrisi orijinde belirtilen açı kadar saat yönünde döndürür. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Geçerli nesne tarafından temsil edilen matrisi belirtilen nokta etrafında belirtilen açı kadar saat yönünde döndürür. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Geçerli nesne tarafından temsil edilen matrisi belirtilen nokta etrafında belirtilen açı kadar saat yönünde döndürür. |
| void [Scale](./scale/)(**float**, **float**) | Geçerli nesne tarafından temsil edilen matrise belirtilen ölçek vektörünü uygular. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Geçerli nesne tarafından temsil edilen matrise belirtilen ölçek vektörünü uygular. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n. şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Shear](./shear/)(**float**, **float**) | Geçerli nesne tarafından temsil edilen matrise belirtilen kayma vektörünü uygular. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Geçerli nesne tarafından temsil edilen matrise belirtilen kayma vektörünü uygular. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özelleştirilmiş nesnelerin dizeye dönüştürülmesini sağlar. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin tanımladığı geometrik dönüşümü belirtilen noktalara uygular. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin tanımladığı geometrik dönüşümü belirtilen noktalara uygular. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin tanımladığı geometrik dönüşümü belirtilen noktalara uygular. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin tanımladığı geometrik dönüşümü belirtilen noktalara uygular. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin yalnızca ölçek ve döndürme bileşenlerini belirtilen noktalara uygular. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin yalnızca ölçek ve döndürme bileşenlerini belirtilen noktalara uygular. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin yalnızca ölçek ve döndürme bileşenlerini belirtilen noktalara uygular. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Geçerli nesne tarafından temsil edilen matrisin yalnızca ölçek ve döndürme bileşenlerini belirtilen noktalara uygular. |
| void [Translate](./translate/)(**float**, **float**) | Geçerli nesne tarafından temsil edilen matrise belirtilen çeviri vektörünü uygular. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Geçerli nesne tarafından temsil edilen matrise belirtilen çeviri vektörünü uygular. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidi açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Bir dizideki her vektörü geçerli nesne tarafından temsil edilen matrisle çarpar. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Bir dizideki her vektörü geçerli nesne tarafından temsil edilen matrisle çarpar. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Matrix](./~matrix/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Drawing::Drawing2D](../)
* Kütüphane [Aspose.Slides](../../)