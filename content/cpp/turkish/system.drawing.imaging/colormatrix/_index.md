---
title: ColorMatrix
second_title: "Aspose.Slides için C++ API Referansı"
description: "RGBAW renk uzayı için koordinatları içeren 5x5 bir matrisi temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığında veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin."
type: docs
weight: 27
url: /tr/system.drawing.imaging/colormatrix/
---
## ColorMatrix sınıfı

RGBAW renk uzayı için koordinatları içeren 5x5 bir matris temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya new operatörüyle oluşturmayın, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class ColorMatrix : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | [ColorMatrix](./) sınıfının yeni bir örneğini oluşturur ve kimlik matrisinin değerleriyle başlatır. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | [ColorMatrix](./) sınıfının yeni bir örneğini oluşturur ve belirtilen değerlerle başlatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **float** [get_Matrix00](./get_matrix00/)() const | 0. satır ve 0. sütundaki değeri döndürür. |
| **float** [get_Matrix01](./get_matrix01/)() const | 0. satır ve 1. sütundaki değeri döndürür. |
| **float** [get_Matrix02](./get_matrix02/)() const | 0. satır ve 2. sütundaki değeri döndürür. |
| **float** [get_Matrix03](./get_matrix03/)() const | 0. satır ve 3. sütundaki değeri döndürür. |
| **float** [get_Matrix04](./get_matrix04/)() const | 0. satır ve 4. sütundaki değeri döndürür. |
| **float** [get_Matrix10](./get_matrix10/)() const | 1. satır ve 0. sütundaki değeri döndürür. |
| **float** [get_Matrix11](./get_matrix11/)() const | 1. satır ve 1. sütundaki değeri döndürür. |
| **float** [get_Matrix12](./get_matrix12/)() const | 1. satır ve 2. sütundaki değeri döndürür. |
| **float** [get_Matrix13](./get_matrix13/)() const | 1. satır ve 3. sütundaki değeri döndürür. |
| **float** [get_Matrix14](./get_matrix14/)() const | 1. satır ve 4. sütundaki değeri döndürür. |
| **float** [get_Matrix20](./get_matrix20/)() const | 2. satır ve 0. sütundaki değeri döndürür. |
| **float** [get_Matrix21](./get_matrix21/)() const | 2. satır ve 1. sütundaki değeri döndürür. |
| **float** [get_Matrix22](./get_matrix22/)() const | 2. satır ve 2. sütundaki değeri döndürür. |
| **float** [get_Matrix23](./get_matrix23/)() const | 2. satır ve 3. sütundaki değeri döndürür. |
| **float** [get_Matrix24](./get_matrix24/)() const | 2. satır ve 4. sütundaki değeri döndürür. |
| **float** [get_Matrix30](./get_matrix30/)() const | 3. satır ve 0. sütundaki değeri döndürür. |
| **float** [get_Matrix31](./get_matrix31/)() const | 3. satır ve 1. sütundaki değeri döndürür. |
| **float** [get_Matrix32](./get_matrix32/)() const | 3. satır ve 2. sütundaki değeri döndürür. |
| **float** [get_Matrix33](./get_matrix33/)() const | 3. satır ve 3. sütundaki değeri döndürür. |
| **float** [get_Matrix34](./get_matrix34/)() const | 3. satır ve 4. sütundaki değeri döndürür. |
| **float** [get_Matrix40](./get_matrix40/)() const | 4. satır ve 0. sütundaki değeri döndürür. |
| **float** [get_Matrix41](./get_matrix41/)() const | 4. satır ve 1. sütundaki değeri döndürür. |
| **float** [get_Matrix42](./get_matrix42/)() const | 4. satır ve 2. sütundaki değeri döndürür. |
| **float** [get_Matrix43](./get_matrix43/)() const | 4. satır ve 3. sütundaki değeri döndürür. |
| **float** [get_Matrix44](./get_matrix44/)() const | 4. satır ve 4. sütundaki değeri döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkilendirilmiş referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| **float** [idx_get](./idx_get/)(int, int) | Belirtilen satır ve sütundaki değeri döndürür. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Matristeki belirtilen konuma değeri ayarlar. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur ve tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Matrix00](./set_matrix00/)(**float**) | 0. satır ve 0. sütundaki değeri ayarlar. |
| void [set_Matrix01](./set_matrix01/)(**float**) | 0. satır ve 1. sütundaki değeri ayarlar. |
| void [set_Matrix02](./set_matrix02/)(**float**) | 0. satır ve 2. sütundaki değeri ayarlar. |
| void [set_Matrix03](./set_matrix03/)(**float**) | 0. satır ve 3. sütundaki değeri ayarlar. |
| void [set_Matrix04](./set_matrix04/)(**float**) | 0. satır ve 4. sütundaki değeri ayarlar. |
| void [set_Matrix10](./set_matrix10/)(**float**) | 1. satır ve 0. sütundaki değeri ayarlar. |
| void [set_Matrix11](./set_matrix11/)(**float**) | 1. satır ve 1. sütundaki değeri ayarlar. |
| void [set_Matrix12](./set_matrix12/)(**float**) | 1. satır ve 2. sütundaki değeri ayarlar. |
| void [set_Matrix13](./set_matrix13/)(**float**) | 1. satır ve 3. sütundaki değeri ayarlar. |
| void [set_Matrix14](./set_matrix14/)(**float**) | 1. satır ve 4. sütundaki değeri ayarlar. |
| void [set_Matrix20](./set_matrix20/)(**float**) | 2. satır ve 0. sütundaki değeri ayarlar. |
| void [set_Matrix21](./set_matrix21/)(**float**) | 2. satır ve 1. sütundaki değeri ayarlar. |
| void [set_Matrix22](./set_matrix22/)(**float**) | 2. satır ve 2. sütundaki değeri ayarlar. |
| void [set_Matrix23](./set_matrix23/)(**float**) | 2. satır ve 3. sütundaki değeri ayarlar. |
| void [set_Matrix24](./set_matrix24/)(**float**) | 2. satır ve 4. sütundaki değeri ayarlar. |
| void [set_Matrix30](./set_matrix30/)(**float**) | 3. satır ve 0. sütundaki değeri ayarlar. |
| void [set_Matrix31](./set_matrix31/)(**float**) | 3. satır ve 1. sütundaki değeri ayarlar. |
| void [set_Matrix32](./set_matrix32/)(**float**) | 3. satır ve 2. sütundaki değeri ayarlar. |
| void [set_Matrix33](./set_matrix33/)(**float**) | 3. satır ve 3. sütundaki değeri ayarlar. |
| void [set_Matrix34](./set_matrix34/)(**float**) | 3. satır ve 4. sütundaki değeri ayarlar. |
| void [set_Matrix40](./set_matrix40/)(**float**) | 4. satır ve 0. sütundaki değeri ayarlar. |
| void [set_Matrix41](./set_matrix41/)(**float**) | 4. satır ve 1. sütundaki değeri ayarlar. |
| void [set_Matrix42](./set_matrix42/)(**float**) | 4. satır ve 2. sütundaki değeri ayarlar. |
| void [set_Matrix43](./set_matrix43/)(**float**) | 4. satır ve 3. sütundaki değeri ayarlar. |
| void [set_Matrix44](./set_matrix44/)(**float**) | 4. satır ve 4. sütundaki değeri ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n. şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilitlemesini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Drawing::Imaging](../)
* Kütüphane [Aspose.Slides](../../)