---
title: ImageFormat
second_title: Aspose.Slides for C++ API Referansı
description: "Bir görüntünün dosya biçimini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya new operatörüyle oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya assert hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 131
url: /tr/system.drawing.imaging/imageformat/
---
## ImageFormat sınıfı

Bir görüntünün dosya biçimini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya new operatörüyle oluşturmaya çalışmayın; aksi takdirde çalışma zamanı hataları ve/veya assert hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ImageFormat : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | Geçerli ve belirtilen nesneler tarafından temsil edilen görüntü formatlarının eşit olup olmadığını belirler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzı referans tipi nesnelerini karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değerle (NaN dahil) eşit olmadığı halde iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değerle (NaN dahil) eşit olmadığı halde iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne bitmap görüntü formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne geliştirilmiş metafile formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne Değiştirilebilir [Image](../../system.drawing/image/) Dosya (Exif) formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne [Graphics](../../system.drawing/graphics/) Interchange Format (GIF) görüntü formatını temsil eder. |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | Geçerli nesne tarafından temsil edilen görüntü formatıyla ilişkili GUID'i döndürür. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne [Windows](../../system.windows/) ikon görüntü formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne Joint Photographic Experts Group (JPEG) görüntü formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne bellekteki bir bitmap formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG) görüntü formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne Tagged [Image](../../system.drawing/image/) File Format (TIFF) görüntü formatını temsil eder. |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | [ImageFormat](./) nesnesine işaret eden paylaşımlı bir işaretçi döndürür; bu nesne [Windows](../../system.windows/) metafile (WMF) görüntü formatını temsil eder. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğudur. Özel nesnelerin hash'lenmesini etkinleştirir. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğudur. |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | [ImageFormat](./) sınıfının bir örneğini oluşturur; bu sınıf belirtilen GUID ile ilişkili bir görüntü formatını temsil eder. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTür tarafından tanımlanan türe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğudur. Özel tiplerin kopyalanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını ilklendirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz; sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz; sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapımını mümkün kılar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hâli. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hâli. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | Bu [ImageFormat](./) nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Diğer

* Sınıf [Object](../../system/object/)
* İsim alanı [System::Drawing::Imaging](../)
* Kütüphane [Aspose.Slides](../../)