---
title: Rotation3D
second_title: Aspose.Slides for C++ API Referansı
description: Bir grafiğin 3D döndürmesini temsil eder.
type: docs
weight: 1327
url: /tr/aspose.slides.charts/rotation3d/
---
## Rotation3D sınıfı

Bir grafiğin 3D döndürmesini temsil eder.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere (NaN dahil) eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere (NaN dahil) eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Bir 3D grafiğin derinliğini, grafik genişliğinin yüzde olarak (20 ila 2000 yüzde arasında) döndürür. **uint16_t** okunur. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Bir 3D grafiğin yüksekliğini, grafik genişliğinin yüzde olarak (5 ila 500 yüzde arasında) belirtir. **uint16_t** okunur. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | 3D grafikler için perspektif değerini (görüş alanı açısı) (0 ile 240 arasında) döndürür. RightAngleAxes özelliği true ise yoksayılır. **uint8_t** okunur. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Grafik eksenlerinin perspektif yerine dik açıyla olup olmadığını belirler. Başka bir deyişle, eksen açıların grafik dönüşü veya eğiminden bağımsız olup olmadığını belirler. **bool** okunur. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | X ekseni etrafındaki döndürme derecesini (Y yönünde) (-90 ile 90 derece arasında) döndürür. Özellik ECMA-376'daki 21.2.2.157 rotX (X Rotation) öğesi ve PowerPoint 2007+ "Y Rotation" seçeneği ile eşleşir. **int8_t** okunur. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Y ekseni etrafındaki döndürme derecesini (X yönünde) (0 ile 360 derece arasında) döndürür. Özellik ECMA-376'daki 21.2.2.158 rotY (Y Rotation) öğesi ve PowerPoint 2007+ "X Rotation" seçeneği ile eşleşir. **uint16_t** okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özelleştirilmiş nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Bir 3D grafiğin derinliğini, grafik genişliğinin yüzde olarak (20 ila 2000 yüzde arasında) ayarlar. **uint16_t** yazar. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Bir 3D grafiğin yüksekliğini, grafik genişliğinin yüzde olarak (5 ila 500 yüzde arasında) belirtir. **uint16_t** yazar. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | 3D grafikler için perspektif değerini (görüş alanı açısı) (0 ile 240 arasında) ayarlar. RightAngleAxes özelliği true ise yoksayılır. **uint8_t** yazar. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Grafik eksenlerinin perspektif yerine dik açıyla olup olmadığını belirler. Başka bir deyişle, eksen açıların grafik dönüşü veya eğiminden bağımsız olup olmadığını belirler. **bool** yazar. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | X ekseni etrafındaki döndürme derecesini (Y yönünde) (-90 ile 90 derece arasında) ayarlar. Özellik ECMA-376'daki 21.2.2.157 rotX (X Rotation) öğesi ve PowerPoint 2007+ "Y Rotation" seçeneği ile eşleşir. **int8_t** yazar. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Y ekseni etrafındaki döndürme derecesini (X yönünde) (0 ile 360 derece arasında) ayarlar. Özellik ECMA-376'daki 21.2.2.158 rotY (Y Rotation) öğesi ve PowerPoint 2007+ "X Rotation" seçeneği ile eşleşir. **uint16_t** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstergeleri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit kaldırmasını uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [IRotation3D](../irotation3d/)
* Sınıf [IDOMObject](../../aspose.slides/idomobject/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)