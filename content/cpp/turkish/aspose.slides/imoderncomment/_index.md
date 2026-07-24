---
title: IModernComment
second_title: Aspose.Slides for C++ API Referansı
description: Bir slayttaki yorumu temsil eder.
type: docs
weight: 2965
url: /tr/aspose.slides/imoderncomment/
---
## IModernComment sınıfı

Bir slayttaki yorumu temsil eder.

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989’a göre NaN hiçbir değerle, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı çift hassasiyetli kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989’a göre NaN hiçbir değerle, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | Yorumun yazarını döndürür. Salt-okunur [ICommentAuthor](../icommentauthor/). |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | Yorumun oluşturulma zamanını döndürür. Bu özelliği [DateTime::MinValue](../../system/datetime/minvalue/) olarak ayarlamak, yorum zamanı ayarlanmadığını gösterir. Okunur [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | Üst yorumu alır. Okunur [IComment](../icomment/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | Yorumun slayttaki konumunu döndürür. Okunur [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | Yorumla ilişkili bir şekli döndürür. Salt-okunur [IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | Yorumun üst slaytını döndürür. Salt-okunur [ISlide](../islide/). |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | Yorumun durumunu döndürür. Okunur [ModernCommentStatus](../moderncommentstatus/). |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | Slayt yorumunun düz metnini döndürür. Okunur [System::String](../../system/string/). |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | Eğer yorum [AutoShape](../autoshape/) ile ilişkiliyse metin çerçevesindeki metin seçimi uzunluğunu döndürür. Okunur **int32_t**. |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | Eğer yorum [AutoShape](../autoshape/) ile ilişkiliyse metin çerçevesindeki metin seçiminin başlangıç konumunu döndürür. Okunur **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin karma (hash) oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözlem (sentry) nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel türlerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| virtual void [Remove](../icomment/remove/)() | Yorumu ve tüm yanıtlarını üst koleksiyondan kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | Yorumun oluşturulma zamanını ayarlar. Bu özelliği [DateTime::MinValue](../../system/datetime/minvalue/) olarak ayarlamak, yorum zamanının ayarlanmadığını gösterir. Yazılabilir [System::DateTime](../../system/datetime/). |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | Üst yorumu ayarlar. Yazılabilir [IComment](../icomment/). |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Yorumun slayttaki konumunu ayarlar. Yazılabilir [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | Yorumun durumunu ayarlar. Yazılabilir [ModernCommentStatus](../moderncommentstatus/). |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | Slayt yorumunun düz metnini ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | Eğer yorum [AutoShape](../autoshape/) ile ilişkiliyse metin çerçevesindeki metin seçimi uzunluğunu ayarlar. Yazılabilir **int32_t**. |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | Eğer yorum [AutoShape](../autoshape/) ile ilişkiliyse metin çerçevesindeki metin seçiminin başlangıç konumunu ayarlar. Yazılabilir **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesneleri stringe dönüştürmeyi sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [IComment](../icomment/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)