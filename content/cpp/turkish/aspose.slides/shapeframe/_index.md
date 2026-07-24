---
title: ShapeFrame
second_title: C++ için Aspose.Slides API Referansı
description: Şekil çerçevesinin özelliklerini temsil eder.
type: docs
weight: 5136
url: /tr/aspose.slides/shapeframe/
---
## ShapeFrame sınıfı


Shape frame'in özelliklerini temsil eder.

```cpp
class ShapeFrame : public Aspose::Slides::IShapeFrame
```

## Metotlar

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klonlar |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [CloneT](./clonet/)() override | Klonlar. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bu örneğin belirtilen nesneye eşit olup olmadığını gösteren bir değer döndürür. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ShapeFrame](./)\>) | Bu örneğin belirtilen nesneye eşit olup olmadığını gösteren bir değer döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **float** [get_CenterX](./get_centerx/)() override | Bir çerçevenin merkezinin X koordinatını döndürür. Yalnızca okunabilir **float**. |
| **float** [get_CenterY](./get_centery/)() override | Bir çerçevenin merkezinin Y koordinatını döndürür. Yalnızca okunabilir **float**. |
| [NullableBool](../nullablebool/) [get_FlipH](./get_fliph/)() override | Bir çerçevenin yatay olarak çevrilip çevrilmediğini belirler. Yalnızca okunabilir [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_FlipV](./get_flipv/)() override | Bir çerçevenin dikey olarak çevrilip çevrilmediğini belirler. Yalnızca okunabilir [NullableBool](../nullablebool/). |
| **float** [get_Height](./get_height/)() override | Bir çerçevenin yüksekliğini döndürür. Yalnızca okunabilir **float**. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() override | Bir çerçevenin koordinatlarını döndürür. Yalnızca okunabilir [System::Drawing::RectangleF](../../system.drawing/rectanglef/). |
| **float** [get_Rotation](./get_rotation/)() override | Bir çerçevenin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürülür. Yalnızca okunabilir **float**. |
| **float** [get_Width](./get_width/)() override | Bir çerçevenin genişliğini döndürür. Yalnızca okunabilir **float**. |
| **float** [get_X](./get_x/)() override | Bir çerçevenin sol üst köşesinin X koordinatını döndürür. Yalnızca okunabilir **float**. |
| **float** [get_Y](./get_y/)() override | Bir çerçevenin sol üst köşesinin Y koordinatını döndürür. Yalnızca okunabilir **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Bu nesne için bir karma kod döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırılabilir veya [LockContext](../../system/lockcontext/) gözcü nesnesi kullanılabilir. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Stringler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
|  [ShapeFrame](./shapeframe/)(**float**, **float**, **float**, **float**, [NullableBool](../nullablebool/), [NullableBool](../nullablebool/), **float**) | Yeni şekil çerçevesi özelliklerini oluşturur. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dize dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırılabilir veya [LockContext](../../system/lockcontext/) gözcü nesnesi kullanılabilir. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [IShapeFrame](../ishapeframe/)
* İsim Uzayı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)