---
title: Pen
second_title: Aspose.Slides for C++ API Referansı
description: "Çizilen satır ve eğrilerin renk, genişlik vb. gibi özelliklerini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tür bir örnek yığını üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 183
url: /tr/system.drawing/pen/
---
## Pen sınıfı

Çizilen satır ve eğrilerin color, width gibi özelliklerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tür bir örnek yığını üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Pen : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | Geçerli nesnenin bir kopyasını döndürür. |
| void [Dispose](./dispose/)() | Geçerli nesne tarafından edinilen tüm işletim kaynaklarını serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | Geçerli [Pen](./) nesnesinin hizalamasını gösteren bir değer döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | Bu kalemin [Brush](../brush/) nesnesini döndürür. |
| [Color](../color/) [get_Color](./get_color/)() const | Bu kalemin rengini döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | Bileşik bir kalemi belirten değer dizisini döndürür. |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | Kesikli bir çizginin her iki ucunda kullanılan ucu gösteren bir değer döndürür. |
| **float** [get_DashOffset](./get_dashoffset/)() const | Bir çizginin başlangıcından kesikli desenin başlangıcına olan mesafeyi döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | Kesikli bir çizgide özel kesik desenini gösteren bir dizi döndürür. |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | Geçerli [Pen](./) nesnesinin kesik stilini gösteren bir değer döndürür. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | Geçerli [Pen](./) nesnesinin bitiş çizgi ucunu gösteren bir değer döndürür. |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | Bu [Pen](./) nesnesiyle çizilen çizgilerin nasıl birleştirildiğini gösteren bir değer döndürür. |
| **float** [get_MiterLimit](./get_miterlimit/)() const | Miter köşesindeki eklemin kalınlık sınırını döndürür. |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | UYGULANMADI. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | Geçerli [Pen](./) nesnesinin başlangıç çizgi ucunu gösteren bir değer döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | Geçerli nesne tarafından temsil edilen kalem için geometrik dönüşümleri belirten bir Matrix nesnesinin kopyasını döndürür. |
| **float** [get_Width](./get_width/)() const | Geçerli [Pen](./) nesnesinin genişliğini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Geçerli nesnenin dönüşüm matrisini belirtilen matrisle çarpar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
|  [Pen](./pen/)(const [Color](../color/)\&) | Belirtilen rengi temsil eden yeni bir [Pen](./) nesnesi oluşturur. |
|  [Pen](./pen/)(const [Color](../color/)\&, **float**) | Belirtilen renk ve genişliği temsil eden yeni bir [Pen](./) nesnesi oluşturur. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Yeni bir [Pen](./) nesnesi oluşturur ve belirtilen [Brush](../brush/) nesnesiyle başlatır. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | Yeni bir [Pen](./) nesnesi oluşturur ve belirtilen [Brush](../brush/) nesnesiyle başlatır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleşmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleşmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [ResetTransform](./resettransform/)() | Geçerli nesnenin dönüşüm matrisini sıfırlar ve birim matris haline getirir. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Yerel geometrik dönüşümü belirtilen açıda, belirtilen sırada döndürür. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Yerel geometrik dönüşümü belirtilen faktörlerle, belirtilen sırada ölçeklendirir. |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | Geçerli [Pen](./) nesnesinin hizalamasını ayarlar. |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Bu kalemin [Brush](../brush/) nesnesini ayarlar. |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | Bu kalemin rengini ayarlar. |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Bileşik bir kalemi belirten değer dizisini ayarlar. |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Özel bitiş çizgi ucunu ayarlar. |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Özel başlangıç çizgi ucunu ayarlar. |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | Kesikli bir çizginin her iki ucunda kullanılan ucu belirten bir değeri ayarlar. |
| void [set_DashOffset](./set_dashoffset/)(**float**) | Bir çizginin başlangıcından kesik desenin başlangıcına olan mesafeyi ayarlar. |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Kesikli bir çizgide özel kesik desenini belirten bir dizi ayarlar. Dizi, alternatif kesik ve boşluk uzunluklarını belirten sayılardan oluşur. |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | Geçerli [Pen](./) nesnesinin kesik stilini belirten bir değeri ayarlar. |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Geçerli [Pen](./) nesnesinin bitiş çizgi ucunu ayarlar. |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | Bu [Pen](./) nesnesiyle çizilen çizgilerin nasıl birleştirileceğini belirten bir değeri ayarlar. |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | Miter köşesindeki eklemin kalınlık sınırını ayarlar. |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Geçerli [Pen](./) nesnesinin başlangıç çizgi ucunu ayarlar. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Geçerli nesne tarafından temsil edilen kalem için geometrik dönüşümleri belirten bir Matrix nesnesi ayarlar. |
| void [set_Width](./set_width/)(**float**) | Geçerli [Pen](./) nesnesinin genişliğini ayarlar. |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | UYGULANMADI. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)