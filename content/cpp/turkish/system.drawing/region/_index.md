---
title: Region
second_title: Aspose.Slides for C++ API Referansı
description: "Bir grafik şeklinin iç kısmını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığıta (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 261
url: /tr/system.drawing/region/
---
## Region sınıfı

Bir grafik şeklinin iç kısmını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Region : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Geçerli nesnenin bir kopyasını döndürür. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen dikdörtgen tarafından tanımlanan ve bu regionla kesişmeyen bölümüyle değiştirir. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen dikdörtgen tarafından tanımlanan ve bu regionla kesişmeyen bölümüyle değiştirir. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen yol (path) tarafından tanımlanan ve bu regionla kesişmeyen bölümüyle değiştirir. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen regionun bu regionla kesişmeyen bölümüyle değiştirir. |
| void [Dispose](./dispose/)() | Geçerli nesne tarafından edinilen tüm işletim sistemi kaynaklarını serbest bırakır. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Belirtilen regionun, belirtilen çizim yüzeyinde geçerli nesne tarafından temsil edilen region ile aynı olup olmadığını belirler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen dikdörtgen tarafından tanımlanan regionun dışlanması sonucu elde edilenle değiştirir. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen dikdörtgen tarafından tanımlanan regionun dışlanması sonucu elde edilenle değiştirir. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen yol (path) tarafından tanımlanan regionun dışlanması sonucu elde edilenle değiştirir. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Geçerli nesne tarafından temsil edilen regionu, belirtilen regionun dışlanması sonucu elde edilenle değiştirir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bu [Region](./) nesnesini, bir [Graphics](../graphics/) nesnesinin çizim yüzeyinde sınırlayan bir dikdörtgeni temsil eden bir [RectangleF](../rectanglef/) yapısını alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Geçerli nesne tarafından temsil edilen regionu tanımlayan verileri içeren bir RegionData nesnesi döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Belirtilen matris dönüşümü uygulandıktan sonra bu [Region](./) öğesini yaklaşık olarak temsil eden bir dizi [RectangleF](../rectanglef/) yapısı döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen dikdörtgen tarafından tanımlanan bir regionun kesişimi sonucu elde edilenle değiştirir. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen dikdörtgen tarafından tanımlanan bir regionun kesişimi sonucu elde edilenle değiştirir. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen yol (path) tarafından tanımlanan bir regionun kesişimi sonucu elde edilenle değiştirir. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen regionun kesişimi sonucu elde edilenle değiştirir. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Belirtilen çizim yüzeyinde geçerli nesne tarafından temsil edilen regionun boş bir iç yapısı olup olmadığını belirler. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Belirtilen çizim yüzeyinde geçerli nesne tarafından temsil edilen regionun sonsuz bir iç yapısı olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Belirtilen noktanın geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Belirtilen noktanın geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Belirtilen dikdörtgenin herhangi bir bölümünün geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Belirtilen dikdörtgenin herhangi bir bölümünün geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Belirtilen noktanın, belirtilen grafikler kullanılarak geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Belirtilen noktanın, belirtilen grafikler kullanılarak geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen grafikler kullanılarak geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen grafikler kullanılarak geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Belirtilen noktanın geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Belirtilen noktanın, belirtilen grafikler kullanılarak geçerli nesne tarafından temsil edilen region içinde olup olmadığını belirler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| void [MakeEmpty](./makeempty/)() | Geçerli nesneyi boş bir iç yapıyla başlatır. |
| void [MakeInfinite](./makeinfinite/)() | Bu region nesnesini sonsuz bir iç yapıyla başlatır. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmiş hali. |
|  [Region](./region/)() | [Region](./) sınıfının yeni bir örneğini oluşturur. |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | [Region](./) sınıfının, belirtilen dikdörtgen tarafından tanımlanan bir regionu temsil eden yeni bir örneğini oluşturur. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | [Region](./) sınıfının, belirtilen dikdörtgen tarafından tanımlanan bir regionu temsil eden yeni bir örneğini oluşturur. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | [Region](./) sınıfının, belirtilen yol (path) tarafından tanımlanan bir regionu temsil eden yeni bir örneğini oluşturur. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | [Region](./) sınıfının, belirtilen RegionData nesnesi tarafından tanımlanan bir regionu temsil eden yeni bir örneğini oluşturur. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını arttırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Bu regionu belirtilen matris ile dönüştürür. |
| void [Transform](./transform/)(const SkMatrix\&) | Bu regionu belirtilen matris ile dönüştürür. |
| void [Translate](./translate/)(int, int) | Regionun koordinatlarını belirtilen miktarda kaydırır. |
| void [Translate](./translate/)(**float**, **float**) | Regionun koordinatlarını belirtilen miktarda kaydırır. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen dikdörtgen tarafından tanımlanan bir regionun birleşim işleminin sonucu ile değiştirir. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen dikdörtgen tarafından tanımlanan bir regionun birleşim işleminin sonucu ile değiştirir. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen yol (path) tarafından tanımlanan bir regionun birleşim sonucu ile değiştirir. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen regionun birleşim sonucu ile değiştirir. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit kaldırmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen dikdörtgen tarafından tanımlanan regionun kesişmeyen bölümleriyle değiştirir. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen dikdörtgen tarafından tanımlanan regionun kesişmeyen bölümleriyle değiştirir. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen yol (path) tarafından tanımlanan regionun kesişmeyen bölümleriyle değiştirir. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Geçerli nesne tarafından temsil edilen regionu, bu region ile belirtilen regionun kesişmeyen bölümleriyle değiştirir. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
| virtual  [~Region](./~region/)() | Yıkıcı. |

## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)