---
title: ToBase64String()
second_title: Aspose.Slides for C++ API Referansı
description: Base-64, belirtilen bayt dizisindeki öğeleri kodlar ve kodlanmış veriyi bir dize olarak döndürür.
type: docs
weight: 40
url: /tr/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) method

Base-64, belirtilen bayt dizisindeki öğeleri kodlar ve kodlanmış veriyi bir dize olarak döndürür.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Kodlanacak bayt dizisi |
| insert_line_breaks | **bool** | Her 76 base-64 karakterinden sonra çıktı dizesine satır sonu karakterlerinin eklenip eklenmeyeceğini belirtir |

### Dönüş Değeri

Girdi dizisinin base-64 kodlu temsili içeren dize

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) method

Base-64, belirtilen bayt dizisindeki öğe aralığını kodlar ve kodlanmış veriyi bir dize olarak döndürür.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Kodlanacak öğe aralığını içeren bayt dizisi |
| offset_in | int | Kodlamanın başlayacağı giriş dizisindeki bir öğenin indeksi |
| length | int | Kodlanacak öğe aralığının uzunluğu |
| insert_line_breaks | **bool** | Her 76 base-64 karakterinden sonra çıktı dizesine satır sonu karakterlerinin eklenip eklenmeyeceğini belirtir |

### Dönüş Değeri

Giriş dizisinin öğe aralığının base-64 kodlu temsili içeren dize

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) method

Base-64, belirtilen bayt dizisindeki öğeleri kodlar ve kodlanmış veriyi bir dize olarak döndürür.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Kodlanacak bayt dizisi |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 kodlu verinin biçimlendirme seçeneklerini belirtir |

### Dönüş Değeri

Girdi dizisinin base-64 kodlu temsili içeren dize

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) method

Base-64, belirtilen bayt dizisindeki öğe aralığını kodlar ve kodlanmış veriyi bir dize olarak döndürür.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Kodlanacak öğe aralığını içeren bayt dizisi |
| offset_in | int | Kodlamanın başlayacağı giriş dizisindeki bir öğenin indeksi |
| length | int | Kodlanacak öğe aralığının uzunluğu |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 kodlu verinin biçimlendirme seçeneklerini belirtir |

### Dönüş Değeri

Giriş dizisinin öğe aralığının base-64 kodlu temsili içeren dize

## İlgili

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [String](../../string/)
* Yapı [Convert](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)