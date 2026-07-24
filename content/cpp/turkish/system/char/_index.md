---
title: Char
second_title: Aspose.Slides for C++ API Referansı
description: UTF-16 kod birimleri olarak temsil edilen karakterlerin işlenmesi için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Onu hiçbir şekilde örneklememelisiniz.
type: docs
weight: 170
url: /tr/system/char/
---
## Char sınıf

UTF-16 kod birimleri olarak temsil edilen karakterlerin işlenmesi için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Onu hiçbir şekilde örneklemek asla yapılmamalıdır.

```cpp
class Char
```

## Yöntemler

| Method | Description |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | UTF-32 kod birimini [System::String](../string/) sınıfının bir örneğine dönüştürür. |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Belirtilen UTF-16 yedek çiftini UTF-32 kod birimine dönüştürür. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Bir dizede belirtilen konumdaki UTF-16 kodlu bir karakterin veya yedek çiftinin değerini UTF-32 kod birimine dönüştürür. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Belirtilen UTF-16 karakterini çift hassasiyetli kayan nokta sayısal değere dönüştürür. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Belirtilen karakterin Unicode kategorisini temsil eden bir değer döndürür. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Belirtilen karakterin ASCII boşluk karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin Unicode kontrol karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Belirtilen karakterin Unicode kontrol karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin ondalık rakam olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Belirtilen dizede belirtilen indeksteki karakterin ondalık rakam olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Belirtilen karakterin ondalık rakam olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Belirtilen dizede belirtilen indeksteki karakterin UTF-16 yüksek yedek kod birimi olup olmadığını belirler. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin yüksek yedek olup olmadığını belirler. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Belirtilen karakterin yüksek yedek olup olmadığını belirler. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin Unicode harfi olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsLetter](./isletter/)(char_t) | Belirtilen karakterin Unicode harfi olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin Unicode harfi veya ondalık rakam olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Belirtilen karakterin Unicode harfi veya ondalık rakam olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin küçük harf olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsLower](./islower/)(char_t) | Belirtilen karakterin küçük harf olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Belirtilen dizede belirtilen indeksteki karakterin küçük harf olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin düşük yedek olup olmadığını belirler. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Belirtilen karakterin düşük yedek olup olmadığını belirler. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin sayı olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Belirtilen karakterin sayı olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin noktalama işareti olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Belirtilen karakterin noktalama işareti olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin ayırıcı karakter olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Belirtilen karakterin ayırıcı karakter olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Belirtilen karakterin UTF-16 yedek kod birimi olup olmadığını belirler. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Belirtilen dizede belirtilen indeksteki karakterin UTF-16 yedek kod birimi olup olmadığını belirler. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Belirtilen iki karakterin bir UTF-16 yedek çifti oluşturup oluşturmadığını belirler. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Belirtilen karakter arabellek içinde iki ardışık karakterin yedek çift olup olmadığını belirler. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin simge karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Belirtilen karakterin simge karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Belirtilen dizede belirtilen indeksteki karakterin büyük harf olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin büyük harf olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsUpper](./isupper/)(char_t) | Belirtilen karakterin büyük harf olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Belirtilen karakter arabellek içinde belirtilen indeksteki karakterin boşluk karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Belirtilen karakterin boşluk karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Belirtilen dizede belirtilen indeksteki karakterin boşluk karakteri olarak sınıflandırılıp sınıflandırılmadığını belirler. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Belirtilen dizenin ilk ve tek karakterini char_t değerine dönüştürür. |
| static char_t [ToLower](./tolower/)(char_t) | Belirtilen karakteri küçük harfe dönüştürür. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Belirtilen karakteri küçük harfe dönüştürür. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Belirtilen karakteri küçük harfe dönüştürür. |
| static char_t [ToUpper](./toupper/)(char_t) | Belirtilen karakteri büyük harfe dönüştürür. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Belirtilen karakteri büyük harfe dönüştürür. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Belirtilen karakteri büyük harfe dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Tek karakter içeren bir dizgeyi UTF-16 karakterine dönüştürmeye çalışır. Fonksiyon yalnızca girdi dizesi null değilse ve tam olarak bir karakter uzunluğunda ise başarılı olur. |

## İlgili

* Namespace [System](../)
* Library [Aspose.Slides](../../)