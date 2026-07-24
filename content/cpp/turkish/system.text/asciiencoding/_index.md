---
title: ASCIIEncoding
second_title: Aspose.Slides için C++ API Referansı
description: "ASCII kodlamasını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1
url: /tr/system.text/asciiencoding/
---
## ASCIIEncoding sınıf

ASCII kodlamasını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya `new` operatörü ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Yöntemler

| Method | Description |
| --- | --- |
|  [ASCIIEncoding](./asciiencoding/)() | Yapıcı. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | Kodlama nesnesini klonlar. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | İki kodlama arasında baytları dönüştürür. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | İki kodlama arasında baytları dönüştürür. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Kodlamaları karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ı eşit kabul eden C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ı eşit kabul eden C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII kodlamasını alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Standart büyük-uçlu Unicode kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Standart büyük-uçlu UTF-32 kodlama nesnesini alır. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | E-posta ajanının gövde uyumlu kodlama adını alır. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) kod sayfası kimliğini alır. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Çözücü geri dönüşünü alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Varsayılan kodlamayı alır. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Kodlayıcı geri dönüşünü alır. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | İnsan tarafından okunabilir kodlama adını alır. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | E-posta ajanı başlık uyumlu kodlama adını alır. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Kodlamanın tarayıcıda içeriği görüntülemek için kullanılabilir olup olmadığını denetler. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Kodlamanın tarayıcıda içeriği kaydetmek için kullanılabilir olup olmadığını denetler. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Kodlamanın e-posta istemcisinde içeriği görüntülemek için kullanılabilir olup olmadığını denetler. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Kodlamanın e-posta istemcisinde içeriği kaydetmek için kullanılabilir olup olmadığını denetler. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Kodlamanın yalnızca okunabilir olup olmadığını denetler. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Kodlamanın tek bayt olup olmadığını denetler. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 kodlamasını alır. DAHİLİ KULLANIM İÇİN. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Standart Unicode kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Standart UTF-7 kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Standart UTF-8 kodlama nesnesini alır. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Yalnızca dahili, sınıf kütüphaneleri tarafından kullanılmak içindir: İşaretlenmemiş ve giriş doğrulaması yapmaz. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA uyumlu kodlama adını alır. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) kod sayfası kimliğini alır. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Karakter tamponunu kodlamak için gereken karakter sayısını alır. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Karakter tamponunu kodladığınızda oluşan baytları alır. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Bayt tamponunu çözmek için gereken karakter sayısını alır. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bayt tamponunu çözmek için gereken karakter sayısını alır. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bayt tamponunu çözmek için gereken karakter sayısını alır. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Bayt tamponunu çözmek için gereken karakter sayısını alır. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Bayt tamponunu çözdüğünüzde oluşan karakterleri alır. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Bayt tamponunu çözdüğünüzde oluşan karakterleri alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bayt tamponunu çözdüğünüzde oluşan karakterleri alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bayt tamponunu çözdüğünüzde oluşan karakterleri alır. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Bayt tamponunu çözdüğünüzde oluşan karakterleri alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Bu nesneye istek yönlendiren bir çözücü alır. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Bu nesneye istek yönlendiren bir kodlayıcı alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | İsimle kodlama alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Kod sayfasıyla kodlama alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Kod sayfasıyla kodlama alır. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | İsimle kodlama alır. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Bilinen kodlamaların listesini alır. |
| int [GetHashCode](../encoding/gethashcode/)() const override | Kodlamayı hashler. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Bilinen karakter sayısına sahip bir dizeyi tutabilecek en fazla bayt sayısını alır. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Belirtilen bayt sayısını çözmek için gereken en fazla karakter sayısını alır. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | Kodlamayı gösteren bayt dizisini döndürür (örn. BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Bayt tamponunu bir dizeye çözer. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Bayt tamponunu bir dizeye çözer. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bayt tamponunu bir dizeye çözer. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Bayt tamponunu bir dizeye çözer. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Bayt tamponunu bir dizeye çözer. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Yapıcı. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# `lock()` ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Kodlamaları kod sayfalarıyla karşılaştırır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipli nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Dize ve nullptr durumunda [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Dizi durumunda [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Çözücü geri dönüşünü ayarlar. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Kodlayıcı geri dönüşünü ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. İşaretçileri konteynerlerde zayıf moda geçişi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağırılmamalıdır; akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döner. Doğrudan çağırılmamalıdır; akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# `typeof([System.Object](../../system/object/))` yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# `lock()` ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağırılmamalıdır; akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağırılmamalıdır; akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Alanlar

| Field | Description |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Varsayılan kod sayfası değeri. |

## Ayrıca Bakınız

* Sınıf [ICUEncoding](../icuencoding/)
* Ad alanı [System::Text](../)
* Kütüphane [Aspose.Slides](../../)