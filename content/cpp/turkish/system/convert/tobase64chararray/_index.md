---
title: ToBase64CharArray()
second_title: Aspose.Slides for C++ API Referansı
description: Base-64, belirtilen bayt dizisindeki bir öğe aralığını kodlar ve kodlanmış veriyi Unicode karakterler dizisi olarak saklar.
type: docs
weight: 27
url: /tr/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) yöntemi


Base-64, belirtilen bayt dizisindeki bir öğe aralığını kodlar ve kodlanmış veriyi Unicode karakterler dizisi olarak saklar.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Kodlanacak öğe aralığını içeren bayt dizisi |
| offset_in | int | Kodlanacak aralığın başladığı giriş dizisindeki bir öğenin indeksi |
| length | int | Kodlanacak öğe aralığının uzunluğu |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Sonuç verisinin konulacağı çıktı dizisine sabit referans |
| offset_out | int | Sonuç verisinin konulmaya başlanacağı çıktı dizisindeki indeks |
| insert_line_breaks | **bool** | Her 76 base-64 karakterinden sonra satır sonu karakterlerinin çıktı dizisine eklenip eklenmeyeceğini belirler |

### Dönüş Değeri

Yazılan karakter sayısı

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) yöntemi


Base-64, belirtilen bayt dizisindeki bir öğe aralığını kodlar ve kodlanmış veriyi Unicode karakterler dizisi olarak saklar.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Kodlanacak öğe aralığını içeren bayt dizisi |
| offset_in | int | Kodlanacak aralığın başladığı giriş dizisindeki bir öğenin indeksi |
| length | int | Kodlanacak öğe aralığının uzunluğu |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Sonuç verisinin konulacağı çıktı dizisine sabit referans |
| offset_out | int | Sonuç verisinin konulmaya başlanacağı çıktı dizisindeki indeks |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 kodlu verinin biçimlendirme seçeneklerini belirler |

### Dönüş Değeri

Yazılan karakter sayısı

## Ayrıca Bakınız

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* AdAlanı [System](../../)
* Library [Aspose.Slides](../../../)