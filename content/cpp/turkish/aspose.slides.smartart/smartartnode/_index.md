---
title: SmartArtNode
second_title: Aspose.Slides for C++ API Referansı
description: Bir SmartArt nesnesinin düğümünü temsil eder
type: docs
weight: 79
url: /tr/aspose.slides.smartart/smartartnode/
---
## SmartArtNode sınıfı

Bir [SmartArt](../smartart/) nesnesinin düğümünü temsil eder

```cpp
class SmartArtNode : public Aspose::Slides::SmartArt::ISmartArtNode
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_BulletFillFormat](./get_bulletfillformat/)() override | Bir düğüm mermisi için doldurma biçimlendirme özelliklerini içeren [FillFormat](../../aspose.slides/fillformat/) nesnesini döndürür. Not: düğmeler için mermi sağlamayan belirli [SmartArt](../smartart/) düzen tipleri için null dönebilir. Salt okunur [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_ChildNode](./get_childnode/)(**int32_t**) override | Belirtilen indeksdeki bu düğümün bir alt düğümünü döndürür. Salt okunur [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_ChildNodes](./get_childnodes/)() override | Geçerli düğümün tüm alt düğümlerinin koleksiyonlarını döndürür. Salt okunur [ISmartArtNodeCollection](../ismartartnodecollection/). |
| **bool** [get_IsAssistant](./get_isassistant/)() override | Düğümü asistan olarak döndürür. **bool** okunur. |
| **bool** [get_IsHidden](./get_ishidden/)() override | Bu düğüm veri modelinde gizli bir düğüm ise true döndürür. Salt okunur **bool**. |
| **int32_t** [get_Level](./get_level/)() override | Düğümün iç içe seviyesini döndürür. Salt okunur **int32_t**. |
| [OrganizationChartLayoutType](../organizationchartlayouttype/) [get_OrganizationChartLayout](./get_organizationchartlayout/)() override | Geçerli düğümle ilişkili organizasyon şeması düzen tipi döndürür. Okunur [OrganizationChartLayoutType](../organizationchartlayouttype/). |
| **int32_t** [get_Position](./get_position/)() override | Kardeş düğümler arasında düğümün sıfır tabanlı konumunu döndürür. **int32_t** okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShape](../ismartartshape/)\> [get_Shape](./get_shape/)(**int32_t**) override | Belirtilen indeksde bu düğümle ilişkili bir şekli döndürür. Salt okunur [Aspose::Slides::SmartArt::ISmartArtShape](../ismartartshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShapeCollection](../ismartartshapecollection/)\> [get_Shapes](./get_shapes/)() override | Düğümle ilişkili tüm şekillerin koleksiyonlarını döndürür. Salt okunur [ISmartArtShapeCollection](../ismartartshapecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | Düğümün metin çerçevesini döndürür. Salt okunur [ITextFrame](../../aspose.slides/itextframe/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarının başlatılmasını yapar. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna yönelik özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna yönelik özelleştirmesi. |
| **bool** [Remove](./remove/)() override | Mevcut düğümü kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_IsAssistant](./set_isassistant/)(**bool**) override | Düğümü asistan olarak ayarlar. **bool** yazılır. |
| void [set_OrganizationChartLayout](./set_organizationchartlayout/)([OrganizationChartLayoutType](../organizationchartlayouttype/)) override | Geçerli düğümle ilişkili organizasyon şeması düzen tipini ayarlar. [OrganizationChartLayoutType](../organizationchartlayouttype/) yazılır. |
| void [set_Position](./set_position/)(**int32_t**) override | Kardeş düğümler arasında düğümün sıfır tabanlı konumunu ayarlar. **int32_t** yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [ISmartArtNode](../ismartartnode/)
* Adalanı [Aspose::Slides::SmartArt](../)
* Kütüphane [Aspose.Slides](../../)