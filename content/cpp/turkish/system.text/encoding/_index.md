---
title: Encoding
second_title: Aspose.Slides for C++ API Referansı
description: Kodlama hizmetleri.
type: docs
weight: 222
url: /tr/system.text/encoding/
---
## Encoding sınıfı

[Encoding](./) servisleri.

```cpp
class Encoding : public System::Object
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Kodlama nesnesini klonlar. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | İki kodlama arasında baytları dönüştürür. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | İki kodlama arasında baytları dönüştürür. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Kodlamaları karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmadığı halde iki NaN'ın eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmadığı halde iki NaN'ın eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | ASCII kodlamasını alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Standart büyük-baytlı (big-endian) Unicode kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Standart büyük-baytlı UTF-32 kodlama nesnesini alır. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Posta ajanı gövdesiyle uyumlu kodlama adını alır. |
| virtual int [get_CodePage](./get_codepage/)() | [Windows](../../system.windows/) kod sayfası kimliğini alır. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Kod çözücü geri dönüşünü alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Varsayılan kodlamayı alır. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Kodlayıcı geri dönüşünü alır. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | İnsan tarafından okunabilir kodlama adını alır. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Posta ajanı başlığıyla uyumlu kodlama adını alır. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Kodlamanın tarayıcıda içeriği görüntülemek için kullanılabilir olup olmadığını denetler. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Kodlamanın tarayıcıda içeriği kaydetmek için kullanılabilir olup olmadığını denetler. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Kodlamanın posta istemcisinde içeriği görüntülemek için kullanılabilir olup olmadığını denetler. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Kodlamanın posta istemcisinde içeriği kaydetmek için kullanılabilir olup olmadığını denetler. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Kodlamanın yalnızca okunabilir olup olmadığını denetler. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Kodlamanın tek bayt olup olmadığını denetler. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Latin1 kodlamasını alır. DAHİLİ KULLANIM İÇİN. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Standart Unicode kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Standart UTF-7 kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Standart UTF-8 kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Yalnızca dahili, sınıf kütüphaneleri tarafından kullanılmak üzere: İşaretlenmemiş ve giriş doğrulaması yapmayan. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | IANA uyumlu kodlama adını alır. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | [Windows](../../system.windows/) kod sayfası kimliğini alır. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Bir karakter tamponunu kodlamak için gereken karakter sayısını alır. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Bir karakter tamponunu kodlamak için gereken karakter sayısını alır. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Bir karakter tamponunu kodlamak için gereken karakter sayısını alır. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Bir dizeyi kodlamak için gereken karakter sayısını alır. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Bir karakter tamponunu kodlamak için gereken karakter sayısını alır. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Bir karakter tamponunu kodlamak için gereken karakter sayısını alır. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Bir karakter tamponunu kodlamanın sonucunda ortaya çıkan baytları alır. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bir bayt tamponunu çözmek için gereken karakter sayısını alır. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bir bayt tamponunu çözmek için gereken karakter sayısını alır. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Bir bayt tamponunu çözmek için gereken karakter sayısını alır. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Bir bayt tamponunu çözmenin sonucunda ortaya çıkan karakterleri alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bir bayt tamponunu çözmenin sonucunda ortaya çıkan karakterleri alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bir bayt tamponunu çözmenin sonucunda ortaya çıkan karakterleri alır. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Bir bayt tamponunu çözmenin sonucunda ortaya çıkan karakterleri alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Bu nesneye istekleri yönlendiren bir kod çözücü alır. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Bu nesneye istekleri yönlendiren bir kodlayıcı alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | İsme göre kodlamayı alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Kod sayfasına göre kodlamayı alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Kod sayfasına göre kodlamayı alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Kod sayfasına göre kodlamayı alır. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Bilinen kodlamaların listesini alır. |
| int [GetHashCode](./gethashcode/)() const override | Kodlamayı hashler. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Belirtilen sayıda karakteri kodlamak için gereken azami bayt sayısını alır. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Belirtilen sayıda baytı çözmek için gereken azami karakter sayısını alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Kodlamayı belirten bir bayt dizisini döndürür (ör. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Bir bayt tamponunu bir dizeye çözer. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Bir bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bir bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Bir bayt tamponunu bir dizeye çözer. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Bir bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bir bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Bir bayt tamponunu bir dizeye çözer. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Bir bayt tamponunu bir dizeye çözer. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan tipten bir örnek olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogu. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Kod çözücü geri dönüşünü ayarlar. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Kodlayıcı geri dönüşünü ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını ortak (shared) değil zayıf (weak) işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Varsayılan kod sayfası değeri. |

## Typedef'lar

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Text](../)
* Kütüphane [Aspose.Slides](../../)