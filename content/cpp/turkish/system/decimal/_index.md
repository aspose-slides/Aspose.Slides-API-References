---
title: Decimal
second_title: Aspose.Slides for C++ API Referansı
description: "Ondalık bir sayıyı temsil eder. Bu tür yığına ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu türün nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 261
url: /tr/system/decimal/
---
## Decimal sınıfı

Ondalık bir sayıyı temsil eder. Bu tür, yığına (stack) tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. [System::SmartPtr](../smartptr/) sınıfını bu türün nesnelerini yönetmek için asla kullanmayın.

```cpp
class Decimal
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Belirtilen iki [Decimal](./) değerini toplar. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Belirtilen değerden büyük veya ona eşit olan en küçük tam sayıyı döndürür. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | İlk [Decimal](./) nesnesi tarafından temsil edilen değerin ikinci [Decimal](./) nesnesi tarafından temsil edilen değerden küçük, eşit veya büyük olup olmadığını belirler. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değerden küçük, eşit veya büyük olup olmadığını belirler. |
| [Decimal](./decimal/)() | 0 değerini temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::int8_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::int16_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::int32_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::int64_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::uint8_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::uint16_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::uint32_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(std::uint64_t) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(**float**) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(**double**) | Belirtilen değeri temsil eden bir örnek oluşturur. |
| explicit [Decimal](./decimal/)(const std::string\&) | std::string sınıfının bir örneği olarak belirtilen dize temsiline sahip bir değeri temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Belirtilen bileşenlerden bir [Decimal](./) nesnesi oluşturur. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | [Decimal](./) sınıfının, belirtilen [Decimal](./) nesnesiyle aynı sayıyı temsil eden bir örnek oluşturur. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | İkili temsili içeren tam sayı dizisinden bir [Decimal](./) sınıfı örneği oluşturur. |
| [Decimal](./decimal/)(std::nullptr_t) | Her zaman ArgumentNullException fırlatır. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | [Decimal](./) sınıfının belirtilen değeri temsil eden bir örnek oluşturur. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Belirtilen iki [Decimal](./) değerini böler. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Geçerli nesne ve belirtilen nesne tarafından temsil edilen değerlerin eşit olup olmadığını belirler. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Geçerli nesne ve belirtilen nesne tarafından temsil edilen değerlerin eşit olup olmadığını belirler. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Belirtilen nesneler tarafından temsil edilen değerlerin eşit olup olmadığını belirler. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Belirtilen değerden küçük veya ona eşit olan en büyük tam sayıyı döndürür. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) belirtilen OLE para birimi değerini eşdeğer [Decimal](./) değerine dönüştürür. UYGULANMADI. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Belirtilen [Decimal](./) nesnesini temsil ettiği değerin ikili temsiline dönüştürür. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) belirtilen [Decimal](./) değerini bayt dizisine dönüştürür. |
| int [GetHashCode](./gethashcode/)() const | Geçerli nesne için bir hash kodu döndürür. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Nesne tip kodunu alır. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Belirtilen iki [Decimal](./) değerini çarpar. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Belirtilen nesne tarafından temsil edilen değerin negatifini temsil eden yeni bir [Decimal](./) sınıfı örneği döndürür. |
| explicit [operator bool](./operator_bool/)() const | Geçerli nesne tarafından temsil edilen değeri boolean değere dönüştürür. |
| explicit [operator double](./operator_double/)() const | Geçerli nesne tarafından temsil edilen değeri çift duyarlıklı kayan nokta değerine dönüştürür. |
| explicit [operator float](./operator_float/)() const | Geçerli nesne tarafından temsil edilen değeri tek duyarlıklı kayan nokta değerine dönüştürür. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Geçerli nesne ve belirtilen nesne tarafından temsil edilen değerlerin eşit olmadığını belirler. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Geçerli nesne tarafından temsil edilen değerin 0'dan farklı olup olmadığını belirler. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen değerlerin modulo işleminden elde edilen değeri temsil eden yeni bir [Decimal](./) sınıfı örneği döndürür. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Geçerli nesneye, geçerli ve belirtilen nesneler tarafından temsil edilen değerlerin modulo işleminden elde edilen yeni bir değeri atar. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen değerlerin çarpımından elde edilen değeri temsil eden yeni bir [Decimal](./) sınıfı örneği döndürür. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Geçerli nesneye, geçerli ve belirtilen nesneler tarafından temsil edilen değerlerin çarpımından elde edilen yeni bir değeri atar. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen değerlerin toplamından elde edilen değeri temsil eden yeni bir [Decimal](./) sınıfı örneği döndürür. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Geçerli nesne tarafından temsil edilen değeri bir artırır. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Geçerli nesneye, geçerli ve belirtilen nesneler tarafından temsil edilen değerlerin toplamından yeni bir değer atar. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Geçerli nesne tarafından temsil edilen değerden belirtilen nesne tarafından temsil edilen değerin çıkarılması sonucunda elde edilen değeri temsil eden yeni bir [Decimal](./) sınıfı örneği döndürür. |
| [Decimal](./) [operator-](./operator_minus/)() const | Geçerli nesne tarafından temsil edilen değerin negatifinden elde edilen değeri temsil eden yeni bir [Decimal](./) sınıfı örneği döndürür. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Geçerli nesne tarafından temsil edilen değeri bir azaltır. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Geçerli nesneye, geçerli nesne tarafından temsil edilen değerden belirtilen nesne tarafından temsil edilen değerin çıkarılması sonucu yeni bir değer atar. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değere bölünmesinden elde edilen değeri temsil eden yeni bir [Decimal](./) sınıfı örneği döndürür. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Geçerli nesneye, geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değere bölünmesinden yeni bir değer atar. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değerden küçük olup olmadığını belirler. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değere küçük ya da eşit olup olmadığını belirler. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Belirtilen nesne tarafından temsil edilen değeri geçerli nesneye atar. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Geçerli nesne ve belirtilen nesne tarafından temsil edilen değerlerin eşit olup olmadığını belirler. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Geçerli nesne tarafından temsil edilen değerin 0 olup olmadığını belirler. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değerden büyük olup olmadığını belirler. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Geçerli nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değere büyük ya da eşit olup olmadığını belirler. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Ondalık bir sayının dize temsili, eşdeğer bir [Decimal](./) sınıfı örneğine dönüştürür. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Ondalık bir sayının dize temsili, belirtilen stilleri kullanarak eşdeğer bir [Decimal](./) sınıfı örneğine dönüştürür. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Ondalık bir sayının dize temsili, belirtilen format sağlayıcıyı kullanarak eşdeğer bir [Decimal](./) sınıfı örneğine dönüştürür. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Ondalık bir sayının dize temsili, belirtilen stil ve format sağlayıcıyı kullanarak eşdeğer bir [Decimal](./) sınıfı örneğine dönüştürür. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | İki [Decimal](./) değerinin bölünmesinden kalanını hesaplar. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri en yakın tam sayıya yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda fonksiyonun davranışını belirler. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Belirtilen değeri, belirtilen kesirli basamak sayısına sahip en yakın değere yuvarlar. Bir parametre, belirtilen değer iki en yakın sayıya eşit uzaklıkta olduğunda fonksiyonun davranışını belirler. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Bir [Decimal](./) değerini diğerinden çıkarır. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | [Decimal](./) değerini 8 bit işaretsiz tamsayı değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | [Decimal](./) değerini çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | [Decimal](./) değerini 16 bit işaretli tamsayı değerine dönüştürür. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | [Decimal](./) değerini 32 bit işaretli tamsayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | [Decimal](./) değerini 64 bit işaretli tamsayı değerine dönüştürür. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) belirtilen [Decimal](./) değerini eşdeğer OLE para birimi değerine dönüştürür. UYGULANMADI. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | [Decimal](./) değerini 8 bit işaretli tamsayı değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | [Decimal](./) değerini tek duyarlıklı kayan nokta sayısına dönüştürür. |
| std::string [ToStdString](./tostdstring/)() const | Nesne tarafından temsil edilen değerin dize temsiline sahip bir std::string örneği döndürür. |
| [String](../string/) [ToString](./tostring/)() const | Nesne tarafından temsil edilen değerin dize temsili döndürür. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Geçerli nesneyi, kültüre özgü format bilgilerini kullanarak dizeye dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Geçerli nesneyi, belirtilen dize formatını ve belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan kültüre özgü format bilgilerini kullanarak dize temsiline dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Nesne tarafından temsil edilen değerin dize temsili döndürür. Dahili kullanım için. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | [Decimal](./) değerini 16 bit işaretsiz tamsayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | [Decimal](./) değerini 32 bit işaretsiz tamsayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | [Decimal](./) değerini 64 bit işaretsiz tamsayı değerine dönüştürür. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Belirtilen [Decimal](./) nesnesi tarafından temsil edilen değerin tam kısım eşit olduğu, tüm kesirli basamaklar atılmış bir değeri temsil eden [Decimal](./) nesnesini döndürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Belirtilen bir sayının dize temsili içeren dizeyi eşdeğer [Decimal](./) değerine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Sağlanan format bilgileri ve sayı stili kullanarak, belirtilen bir sayının dize temsili içeren dizeyi eşdeğer [Decimal](./) değerine dönüştürür. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [Decimal](./) sınıfının tür bilgisini temsil eden [TypeInfo](../typeinfo/) nesnesine bir referans döndürür. |
| [~Decimal](./~decimal/)() | Yıkıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [MaxValue](./maxvalue/) | [Decimal](./) sınıfı tarafından temsil edilebilecek en büyük sayıyı temsil eder. |
| static [MinusOne](./minusone/) | -1 sayısını temsil eder. |
| static [MinValue](./minvalue/) | [Decimal](./) sınıfı tarafından temsil edilebilecek en küçük sayıyı temsil eder. |
| static [One](./one/) | 1 sayısını temsil eder. |
| static [Zero](./zero/) | 0 sayısını temsil eder. |
## Typedef'lar

| Typedef | Açıklama |
| --- | --- |
| [number_type](./number_type/) | Detail::decimal_number_type için bir takma addır. |
## Açıklamalar

```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```
## İlgili

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)