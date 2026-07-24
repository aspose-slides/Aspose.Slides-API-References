---
title: String
second_title: Aspose.Slides for C++ API Referansı
description: "Kütüphane genelinde kullanılan String sınıfı. Kod çevirirken C# System.String yerine geçer. Optimizasyon nedenleriyle bir Object alt sınıfı olarak kabul edilmez. Bu tip yığıt (stack) üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1275
url: /tr/system/string/
---
## String sınıfı

[String](./) sınıfı kütüphane genelinde kullanılır. Kod çevirirken C# [System.String](./) yerine geçer. Optimizasyon nedenleriyle bir [Object](../object/) alt sınıfı olarak kabul edilmez. Bu tür yığına (stack) tahsis edilmeli ve fonksiyonlara değer veya referans olarak geçirilmelidir. [System::SmartPtr](../smartptr/) sınıfını bu tür nesneleri yönetmek için asla kullanmayın.

```cpp
class String
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) C++ tarafında bir değer türüdür ve (kalıtım olmadan) bazı arabirimleri dolaylı olarak uygular. |
| const UChar * [begin](./begin/)() const | Gerçek dize tamponunun başlangıç adresini döndürür. Hiçbir zaman yeniden tahsis etmez. Tamponun null ile sonlandırılmış olacağını garanti etmez. |
| [String](./) [Clone](./clone/)() const | Geçerli dizenin bir kopyasını oluşturur. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | İki alt dizeyi küçük-eşit-büyük karşılaştırır. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | İki alt dizeyi küçük-eşit-büyük karşılaştırır. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | İki diziyi küçük-eşit-büyük karşılaştırır. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | İki diziyi küçük-eşit-büyük karşılaştırır. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | İki diziyi küçük-eşit-büyük karşılaştırır. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | İki diziyi küçük-eşit-büyük karşılaştırır. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Sıralı (ordinal) modda iki diziyi küçük-eşit-büyük karşılaştırır. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Sıralı (ordinal) modda iki diziyi küçük-eşit-büyük karşılaştırır. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | 'less-equals-more' stilinde iki diziyi karşılaştırır. Geçerli kültürü kullanır. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Dizeleri birleştirir. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Dizeleri birleştirir. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Dizeleri birleştirir. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Dizeleri birleştirir. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | str'nin geçerli dizenin bir alt dize olup olmadığını kontrol eder. |
| **bool** [Contains](./contains/)(char16_t) const | Dizenin verilen karakteri içerip içermediğini kontrol eder. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Dize kopyası oluşturur. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Dize karakterlerini mevcut dizi elemanlarına kopyalar. Yeniden boyutlandırma yapılmaz. |
| const UChar * [end](./end/)() const | Gerçek dize tamponunun sonuna işaretçi döndürür. Hiçbir zaman yeniden tahsis etmez. Tamponun null ile sonlandırılmış olacağını garanti etmez. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Dizenin belirtilen alt dize ile bittiğini kontrol eder. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Dizenin belirtilen alt dize ile bittiğini kontrol eder. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Dizenin belirtilen alt dize ile bittiğini kontrol eder. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) eşitlik karşılaştırması. StringComparison enumerasyonu tarafından sunulan çeşitli modlar desteklenir. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) eşitlik karşılaştırması. [System::StringComparison::Ordinal](../stringcomparison/) karşılaştırma modunu kullanır. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | İki dizeyi Ordial karşılaştırma modunda eşitlik karşılaştırması yapar. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | İki dizeyi eşitlik karşılaştırması yapar. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Bir [String](./)'yi ASCII dizesine dönüştürmeye çalışır. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Dizeyi C# stilinde biçimlendirir. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Dizeyi C# stilinde biçimlendirir. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Dizeyi C# stilinde biçimlendirir. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Dizeyi C# stilinde biçimlendirir. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Dizeyi C# stilinde biçimlendirir. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | ASCII dizesinden [String](./) oluşturur. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | ASCII dizesinden [String](./) oluşturur. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | ASCII dizesinden [String](./) oluşturur. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | utf16 dizesinden [String](./) oluşturur. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | utf32 dizesinden [String](./) oluşturur. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | utf8 dizesinden [String](./) oluşturur. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | utf8 dizesinden [String](./) oluşturur. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | utf8 dizesinden [String](./) oluşturur. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | utf8 dizesinden [String](./) oluşturur. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | widestring'den [String](./) oluşturur. |
| int [get_Length](./get_length/)() const | Dize uzunluğunu alır. |
| int [GetHashCode](./gethashcode/)() const | İçindeki dizeyi hash'ler. ICU'da uygulanmıştır, C#'daki hash'lerle aynı değildir. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Alt dize ileri arama. |
| int [IndexOf](./indexof/)(char_t, int) const | Karakter ileri arama. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Alt dizede karakter ileri arama. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Alt dize ileri arama. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Alt dize ileri arama. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Alt dize ileri arama. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Alt dize ileri arama. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Karakter ileri arama. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Bu dizede str'nin tüm karakterlerini sırasıyla arar. İlk karakter bulunursa konumu döner, aksi takdirde ikinci karakteri ve devamını arar. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Geçilen karakterlerin herhangi birini bütün dizede arar. İlk eşleşen karakterin indeksini döndürür. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Alt dizede geçilen karakterlerin herhangi birini arar. İlk eşleşen karakterin indeksini döndürür. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Alt dizede geçilen karakterlerin herhangi birini arar. İlk eşleşen karakterin indeksini döndürür. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Belirtilen konumda alt dizeyi ekler. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Dize nesnesinin [TypeInfo](../typeinfo/) tarafından belirtilen tipe ait olup olmadığını kontrol eder. |
| **bool** [IsAsciiString](./isasciistring/)() const | [String](./) sadece ASCII semboller içeriyorsa gösterir. |
| **bool** [IsEmpty](./isempty/)() const | Dizenin hem null olmamasını hem de boş olmasını kontrol eder. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Unicode dizenin belirtilen normalleştirme biçimi kullanılarak normalleştirilip edilmediğini kontrol eder. |
| **bool** [IsNull](./isnull/)() const | Dizenin null olarak kabul edilip edilmediğini kontrol eder. [String](./) sadece [String()](./string/) yapıcısı ile oluşturulmuş, null dizeden taşınmış, kopyalanmış ya da atanmış veya [reset()](./reset/) yöntemi çağrılmışsa null olur. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Dizenin boş ya da null olarak kabul edilip edilmediğini kontrol eder. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Verilen dizenin null ya da boş olup olmadığını kontrol eder. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Belirtilen dizenin null, boş ya da yalnızca boşluk karakterlerinden oluşup oluşmadığını gösterir. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Dizeyi ayırıcı olarak kullanarak dizi elemanlarını birleştirir. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Dizeyi ayırıcı olarak kullanarak dizi elemanlarını birleştirir. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Dizeyi ayırıcı olarak kullanarak dizi elemanlarını birleştirir. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Dizeyi ayırıcı olarak kullanarak dizi elemanlarını birleştirir. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Alt dize geri arama. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Alt dize geri arama. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Alt dize geri arama. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Alt dize geri arama. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Karakter geri arama. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Karakter geri arama. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Karakter geri arama. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Geçilen karakterlerin herhangi birini bütün dizede geriye doğru arar. İlk bulunan eşleşmenin indeksini döndürür. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Geçilen karakterlerin herhangi birini alt dizede geriye doğru arar. İlk bulunan eşleşmenin indeksini döndürür. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Geçilen karakterlerin herhangi birini alt dizede geriye doğru arar. İlk bulunan eşleşmenin indeksini döndürür. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Unicode dizeyi belirtilen normalleştirme biçimiyle normalleştirir. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Dizeyi salt okunur span'e dönüştürür. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Eşit olmayan karşılaştırma operatörü. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Dizenin null olmadığını kontrol eder. [IsNull()](./isnull/) çağrısıyla aynı mantığı uygular. |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) birleştirme operatörü. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) dize sabiti ya da karakter dize işaretçisiyle birleştirme. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Dizenin sonuna karakter ekler. |
| [String](./) [operator+](./operator_plus/)(int) const | Dizenin sonuna tamsayı değerinin dize temsilini ekler. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Dizenin sonuna işaretsiz tamsayı değerinin dize temsilini ekler. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Dizenin sonuna kayan nokta değerinin dize temsilini ekler. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Dizenin sonuna 64-bit tamsayı değerinin dize temsilini ekler. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Dizenin sonuna referans tipindeki nesnenin dize temsilini ekler. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Dizenin sonuna referans tipindeki nesnenin dize temsilini ekler. |
| [String](./) [operator+](./operator_plus/)(T) const | Dizenin sonuna bool değerinin dize temsilini ekler. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Birleştirme atama operatörü. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Birleştirme atama operatörü. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Dizeleri sıralı karşılaştırır. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Atama operatörü. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Taşıma atama operatörü. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Eşitlik karşılaştırma operatörü. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Dizenin null olup olmadığını denetler. [IsNull()](./isnull/) çağrısı ile aynı mantığı uygular. |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Dizeleri sıralı karşılaştırır. |
| char_t [operator[]](./operator[]/)(int) const | Belirtilen konumdaki karakteri alır. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Orijinal dizenin sol tarafına doldurma ekler. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Orijinal dizenin sağ tarafına doldurma ekler. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Gerçek dize tamponunun son karakterine (varsa) ters yineleyici döndürür. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Geçerli diziden alt dize dışındaki her şeyi ayıklar. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Gerçek dize tamponunun ilk karakterinden önceki (varsa) ters yineleyiciyi döndürür. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Dizideki karakterin tüm oluşumlarını değiştirir. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Bu dizide aramanın tüm oluşumlarını değiştirir. |
| [String](./)\& [reset](./reset/)() | Dizeyi null olarak ayarlar. C#'de 'string_değişkeni = null' ifadesine eşdeğerdir. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Belirtilen konumdaki karakteri ayarlar. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Diziyi karaktere göre bölüştürür. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Diziyi karaktere göre bölüştürür. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Diziyi iki karakterden birine göre böler. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Belirtilen karakterlerden birine göre diziyi böler. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Belirtilen karakterlerden birine göre diziyi böler. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Diziyi alt dizeye göre böler. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Diziyi alt dizeye göre böler. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Diziyi alt dizeye göre böler. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Diziyi alt dizeye göre böler. Şu anda yalnızca sıfır ya da bir elemanlı ayırıcı dizisini destekler. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Dizenin belirtilen alt dizeyle başlayıp başlamadığını denetler. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Dizenin belirtilen alt dizeyle başlayıp başlamadığını denetler. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Dizenin belirtilen alt dizeyle başlayıp başlamadığını denetler. |
| [String](./string/)() | Varsayılan kurucu. Null olarak kabul edilen bir dize nesnesi oluşturur. |
| [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Dize sabitine göre dize oluşturur. Sabiti null sonlandırılmış dize olarak kabul eder, hedef dize uzunluğunu sabit boyutuna göre hesaplar. |
| [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Karakter dize işaretçisine göre dize oluşturur. İşaret edilen diziyi null sonlandırılmış olarak kabul eder, hedef dize uzunluğunu null karaktere göre hesaplar. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Dize sabitine göre dize oluşturur. Sabiti UTF8'de null sonlandırılmış dize olarak kabul eder, hedef dize uzunluğunu sabit boyutuna göre hesaplar. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Karakter dize işaretçisine göre dize oluşturur. İşaret edilen diziyi UTF8'de null sonlandırılmış olarak kabul eder, hedef dize uzunluğunu null karaktere göre hesaplar. |
| [String](./string/)(const char16_t *, int) | Karakter dize işaretçisinden ve açık uzunluktan dize oluşturur. |
| [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | [System.String](./) sınıfının yeni bir örneğini belirtilen salt okunur aralıkta gösterilen Unicode karakterlerine başlatır. |
| [String](./string/)(const char *, int) | Karakter dize işaretçisinden ve açık uzunluktan dize oluşturur. |
| [String](./string/)(const char16_t *, int, int) | Karakter dize işaretçisinden başlangıç konumundan uzunluk kullanarak dize oluşturur. |
| explicit  [String](./string/)(const char16_t, int) | Doldurma kurucusu. |
| [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Nullptr kurucusu. Diğer şablon kurucularıyla öncelikleri çözmek için şablon olarak bildirilir. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Geniş karakter dize sabitine göre dize oluşturur. Sabiti null sonlandırılmış dize olarak kabul eder, hedef dize uzunluğunu sabit boyutuna göre hesaplar. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtülü dönüşümlere izin verilmez. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Geniş karakter dize işaretçisine göre dize oluşturur. İşaret edilen diziyi null sonlandırılmış kabul eder, hedef dize uzunluğunu null karaktere göre hesaplar. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtülü dönüşümlere izin verilmez. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Geniş karakter dize işaretçisinden ve açık uzunluktan dize oluşturur. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtülü dönüşümlere izin verilmez. |
| explicit  [String](./string/)(const **wchar_t**, int) | Doldurma kurucusu. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtülü dönüşümlere izin verilmez. |
| [String](./string/)(const [String](./)\&) | Kopya kurucu. |
| [String](./string/)([String](./)\&&) | Taşıma kurucu. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Tüm karakter dizisini dizeye dönüştürür. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Karakter dizisi alt aralığını dizeye dönüştürür. Parametreler dizi sınırları dışındaysa boş dize oluşturulur. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | UnicodeString'i [String](./) içine sarar. |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Taşıma kurucu. |
| explicit  [String](./string/)(const std::wstring\&) | [String](./)'ı geniş karakter dizisinden oluşturur. |
| explicit  [String](./string/)(const std::u16string\&) | [String](./)'ı utf16 dizesinden oluşturur. |
| explicit  [String](./string/)(const std::string\&) | [String](./)'ı UTF-8 biçiminde sunulan std::string'den oluşturur. |
| explicit  [String](./string/)(const std::u32string\&) | [String](./)'ı std::u32string dizesinden oluşturur. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Alt dize ayıklar. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Alt dize ayıklar. |
| std::string [ToAsciiString](./toasciistring/)() const | Dizeyi std::string'e dönüştürür. ASCII kodlamasını kullanır. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Dizeyi veya alt dizeyi bayt dizisine dönüştürür. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Dizeyi veya alt dizeyi karakter dizisine dönüştürür. |
| [String](./) [ToLower](./tolower/)() const | Dizenin tüm karakterlerini küçük harfe dönüştürür. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Dizenin tüm karakterlerini belirli bir kültür kullanarak küçük harfe dönüştürür. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Dizenin tüm karakterlerini değişmez kültür kullanarak küçük harfe dönüştürür. |
| [String](./) [ToString](./tostring/)() const | [String](./) sınıfını değer türü nesnelerinde [ToString()](./tostring/) çağrıldığında yönetmek için bir sarmalayıcı. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | [String](./) sınıfını değer türü nesnelerinde [ToString()](./tostring/) çağrıldığında yönetmek için bir sarmalayıcı. |
| std::u16string [ToU16Str](./tou16str/)() const | Dizeyi std::u16string'e dönüştürür. |
| std::u32string [ToU32Str](./tou32str/)() const | Dizeyi std::u32string'e dönüştürür. |
| [String](./) [ToUpper](./toupper/)() const | Dizenin tüm karakterlerini büyük harfe dönüştürür. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Dizenin tüm karakterlerini belirli bir kültür kullanarak büyük harfe dönüştürür. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Dizenin tüm karakterlerini değişmez kültür kullanarak büyük harfe dönüştürür. |
| std::string [ToUtf8String](./toutf8string/)() const | Dizeyi std::string'e dönüştürür. UTF-8 kodlamasını kullanır. |
| std::wstring [ToWCS](./towcs/)() const | Dizeyi std::wstring'e dönüştürür. |
| [String](./) [Trim](./trim/)() const | Dizenin başlangıcından ve sonundan tüm boşluk karakterlerini kaldırır. |
| [String](./) [Trim](./trim/)(char_t) const | Verilen karakterin dizenin başlangıcından ve sonundan tüm oluşumlarını kaldırır. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Verilen karakterlerin dizenin başlangıcından ve sonundan tüm oluşumlarını kaldırır. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Verilen karakterlerin dizenin başlangıcından ve sonundan tüm oluşumlarını kaldırır. |
| [String](./) [TrimEnd](./trimend/)() const | Dizenin sonundan tüm boşluk karakterlerini kaldırır. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Verilen karakterin dizenin sonundan tüm oluşumlarını kaldırır. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Verilen karakterlerin dizenin sonundan tüm oluşumlarını kaldırır. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Verilen karakterlerin dizenin sonundan tüm oluşumlarını kaldırır. |
| [String](./) [TrimStart](./trimstart/)() const | Dizenin başlangıcından tüm boşluk karakterlerini kaldırır. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Verilen karakterin dizenin başlangıcından tüm oluşumlarını kaldırır. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Verilen karakterlerin dizenin başlangıcından tüm oluşumlarını kaldırır. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Verilen karakterlerin dizenin başlangıcından tüm oluşumlarını kaldırır. |
| const UChar * [u_str](./u_str/)() const | ICU tarzı null sonlandırılmış tamponu döndürür. Dizeyi yeniden tahsis edebilir. |
| [~String](./~string/)() | Yıkıcı. |

## Alanlar

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Boş dize. |
| static [Null](./null/) | Null dize. |

## Tip tanımları

| Typedef | Description |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Ters yineleyici türü. |

## Açıklamalar

```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Karakter dizisinden bir string oluştur ve yazdır.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Bayt dizisinden bir string oluştur ve yazdır.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Aşağıdaki stringi kırp ve yazdır.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Cümledeki kelime sayısını yazdır.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)