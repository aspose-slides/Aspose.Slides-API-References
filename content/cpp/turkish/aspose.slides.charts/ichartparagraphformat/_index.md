---
title: IChartParagraphFormat
second_title: Aspose.Slides için C++ API Referansı
description: Bir çizelgenin paragraf biçimlendirme özelliklerini temsil eder.
type: docs
weight: 781
url: /tr/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat sınıf


Bir çizelgenin paragraf biçimlendirme özelliklerini temsil eder.

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | Bir paragraftaki metin hizalamasını döndürür. [TextAlignment](../../aspose.slides/textalignment/) okuyun. |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Varsayılan sekme boyutunu döndürür. **float** okuyun. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Bir paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) okuyun. |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Bir paragraftaki yazı tipi hizalamasını döndürür. [Slides::FontAlignment](../../aspose.slides/fontalignment/) okuyun. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Bir paragrafta sarkan noktalama işaretinin kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) okuyun. |
| virtual **float** [get_Indent](./get_indent/)() | Paragrafın İlk Satır Girintisi/Sarkan Girintisini döndürür. Sarkan Girinti negatif değerlerle tanımlanabilir. **float** okuyun. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Bir paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) okuyun. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Paragraftaki sol kenar boşluğunu döndürür. **float** okuyun. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Paragraftaki sağ kenar boşluğunu döndürür. **float** okuyun. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Bir paragrafta Sağa'dan Sola yazımın kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) okuyun. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Paragrafta son satırdan sonraki boşluk miktarını döndürür. **float** okuyun. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Paragrafta ilk satırdan önceki boşluk miktarını döndürür. **float** okuyun. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Paragrafta temel satırlar arasındaki boşluk miktarını döndürür. **float** okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Belirtilen dizindeki paragraf sekmesini döndürür. Yalnızca okunur [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | Paragraf sekmelerini döndürür. Yalnızca okunur [ITabCollection](../../aspose.slides/itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkilendirilmiş referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe bir örnek olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Aslında hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | Paragraftaki metin hizalamasını ayarlar. [TextAlignment](../../aspose.slides/textalignment/) yazın. |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Varsayılan sekme boyutunu ayarlar. **float** yazın. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Bir paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) yazın. |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | Paragrafta bir yazı tipi hizalamasını ayarlar. [Slides::FontAlignment](../../aspose.slides/fontalignment/) yazın. |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | Paragrafta sarkan noktalama işaretinin kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) yazın. |
| virtual void [set_Indent](./set_indent/)(**float**) | Paragrafın İlk Satır Girintisi/Sarkan Girintisini ayarlar. Sarkan Girinti negatif değerlerle tanımlanabilir. **float** yazın. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) yazın. |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Paragrafta sol kenar boşluğunu ayarlar. **float** yazın. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Paragrafta sağ kenar boşluğunu ayarlar. **float** yazın. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | Paragrafta Sağa'dan Sola yazımın kullanılıp kullanılmadığını belirler. [NullableBool](../../aspose.slides/nullablebool/) yazın. |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Paragrafta son satırdan sonraki boşluk miktarını ayarlar. **float** yazın. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Paragrafta ilk satırdan önceki boşluk miktarını ayarlar. **float** yazın. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Paragrafta temel satırlar arasındaki boşluk miktarını ayarlar. **float** yazın. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan değil) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Direkt olarak çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Direkt olarak çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Direkt olarak çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Direkt olarak çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)