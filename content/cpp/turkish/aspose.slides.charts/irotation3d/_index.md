---
title: IRotation3D
second_title: Aspose.Slides for C++ API Referansı
description: Bir çizelgenin 3D dönüşünü temsil eder.
type: docs
weight: 1171
url: /tr/aspose.slides.charts/irotation3d/
---
## IRotation3D sınıfı

Bir çizelgenin 3D dönüşünü temsil eder.

```cpp
class IRotation3D : public virtual System::Object
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | 3D çizelgenin derinliğini çizelge genişliğinin yüzdesi olarak döndürür (20 ile 2000 yüzde arasında). **uint16_t** okunur. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | 3D çizelgenin yüksekliğini çizelge genişliğinin yüzdesi olarak belirtir (5 ile 500 yüzde arasında). **uint16_t** okunur. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | 3D çizelgeler için perspektif değerini (görüş alanı açısı) döndürür (0 ile 100 arasında). RightAngleAxes özelliği değeri true ise yok sayılır. **uint8_t** okunur. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Çizelge eksenlerinin perspektif çizilmek yerine dik açıyla olup olmadığını belirler. Başka bir deyişle eksen açıları çizelge döndürmesi ya da eğiminden bağımsız olup olmadığını belirler. **bool** okunur. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | X ekseni etrafındaki dönüş derecesini döndürür, yani 3D çizelgeler için Y yönünde (-90 ile 90 derece arasında). Özellik ECMA-376'daki 21.2.2.157 rotX (X Rotation) öğesi ve PowerPoint 2007+\'deki "Y Rotation" seçeneğiyle eşleşir. **int8_t** okunur. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Y ekseni etrafındaki dönüş derecesini döndürür, yani 3D çizelgeler için X yönünde (0 ile 360 derece arasında). Özellik ECMA-376'daki 21.2.2.158 rotY (Y Rotation) öğesi ve PowerPoint 2007+\'deki "X Rotation" seçeneğiyle eşleşir. **uint16_t** okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapılmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapılmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özel versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | 3D çizelgenin derinliğini çizelge genişliğinin yüzdesi olarak ayarlar (20 ile 2000 yüzde arasında). **uint16_t** yazar. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | 3D çizelgenin yüksekliğini çizelge genişliğinin yüzdesi olarak belirtir (5 ile 500 yüzde arasında). **uint16_t** yazar. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | 3D çizelgeler için perspektif değerini (görüş alanı açısı) ayarlar (0 ile 100 arasında). RightAngleAxes özelliği true ise yok sayılır. **uint8_t** yazar. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Çizelge eksenlerinin perspektif çizilmek yerine dik açıyla olup olmadığını belirler... **bool** yazar. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | X ekseni etrafındaki dönüş derecesini ayarlar... **int8_t** yazar. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Y ekseni etrafındaki dönüş derecesini ayarlar... **uint16_t** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özelleştirilmiş nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)