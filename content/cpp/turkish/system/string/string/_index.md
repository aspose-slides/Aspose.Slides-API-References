---
title: String()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan yapıcı. Null olarak kabul edilen bir dize nesnesi oluşturur.
type: docs
weight: 14
url: /tr/system/string/string/
---
## String::String() yapıcı

Varsayılan yapıcı. Null olarak kabul edilen bir dize nesnesi oluşturur.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) yapıcı

Dize literaline dayanarak dize oluşturur. Literal'i null sonlu bir dize olarak kabul eder, hedef dize uzunluğunu literal boyutuna göre hesaplar.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T\& | [String](../) literal işaretçisi. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) yapıcı

Karakter dize işaretçisine dayanarak dize oluşturur. İşaret edilen diziyi null sonlu olarak kabul eder, hedef dize uzunluğunu null karakterine göre hesaplar.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | Karakter dize işaretçisi. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) yapıcı

UTF-8'de null sonlu bir dize olarak literal'i kabul ederek dize oluşturur, hedef dize uzunluğunu literal boyutuna göre hesaplar.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T\& | [String](../) literal işaretçisi. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) yapıcı

UTF-8'de null sonlu bir dize olarak işaret edilen karakter dizesine dayanarak dize oluşturur, hedef dize uzunluğunu null karakterine göre hesaplar.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | Karakter dize işaretçisi. |

## String::String(const char16_t *, int) yapıcı

Karakter dize işaretçisinden ve belirtilen uzunluktan dize oluşturur.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char16_t * | [String](../) işaretçisi, literal veya dizi olabilir. |
| length | int | Belirtilen dize uzunluğu |

## String::String(const ReadOnlySpan\<char16_t\>\&) yapıcı

Belirtilen yalnızca-okunur aralıkta gösterilen Unicode karakterlerine sahip [System.String](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Unicode karakterlerinin yalnızca-okunur bir aralığı. |

## String::String(const char *, int) yapıcı

Karakter dize işaretçisinden ve belirtilen uzunluktan dize oluşturur.

```cpp
System::String::String(const char *str, int length)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char * | [String](../) işaretçisi, UTF-8 verilerine, literal veya dizi olabilir. |
| length | int | Belirtilen dize uzunluğu |

## String::String(const char16_t *, int, int) yapıcı

Başlangıç konumundan uzunluk kullanarak karakter dize işaretçisinden dize oluşturur.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char16_t * | [String](../) işaretçisi, literal veya dizi olabilir. |
| start | int | Başlangıç konumu. |
| length | int | [String](../) uzunluğu. |

## String::String(const char16_t, int) yapıcı

Doldurma yapıcı.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ch | const char16_t | Doldurma karakteri. |
| count | int | Hedef uzunluk. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) yapıcı

Nullptr yapıcı. Diğer şablon yapıcılarıyla öncelikleri çözmek için şablon olarak ilan edilmiştir.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | nullptr_t olmalıdır |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) yapıcı

Geniş karakter dizesi literaline dayanarak dize oluşturur. Literal'i null sonlu bir dize olarak kabul eder, hedef dize uzunluğunu literal boyutuna göre hesaplar. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T\& | [String](../) literal işaretçisi. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) yapıcı

Geniş karakter dize işaretçisine dayanarak dize oluşturur. İşaret edilen diziyi null sonlu kabul eder, hedef dize uzunluğunu null karakterine göre hesaplar. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | Karakter dize işaretçisi. |

## String::String(const wchar_t *, int) yapıcı

Geniş karakter dize işaretçisinden ve belirtilen uzunluktan dize oluşturur. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) işaretçisi, literal veya dizi olabilir. |
| length | int | Belirtilen dize uzunluğu |

## String::String(const wchar_t, int) yapıcı

Doldurma yapıcı. **wchar_t** dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ch | const **wchar_t** | Doldurma karakteri. |
| count | int | Hedef uzunluk. |

## String::String(const String\&) yapıcı

Kopyalama yapıcı.

```cpp
System::String::String(const String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) kopyalanacak. |

## String::String(String\&&) yapıcı

Taşıma yapıcı.

```cpp
System::String::String(String &&str) noexcept
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) verisinin taşınacağı. |

## String::String(const ArrayPtr\<char16_t\>\&) yapıcı

Tüm karakter dizisini dizeye dönüştürür.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) dizeye dönüştürmek için. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) yapıcı

Karakter dizisinin alt aralığını dizeye dönüştürür. Parametreler dizi sınırları dışındaysa, boş dize oluşturulur.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Karakter dizisi. |
| offset | int | Alt dizi başlangıç indeksi. |
| len | int | Alt dizi uzunluğu. |

## String::String(const codeporting_icu::UnicodeString\&) yapıcı

UnicodeString'i [String](../) içine sarar.

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString'i [String](../) içine sarmak için. |

## String::String(codeporting_icu::UnicodeString\&&) yapıcı

Taşıma yapıcı.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString'i [String](../) içine sarmak için. |

## String::String(const std::wstring\&) yapıcı

Geniş dizeden [String](../) oluşturur.

```cpp
System::String::String(const std::wstring &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const std::wstring\& | [String](../) içine dönüştürmek için geniş dize. |

## String::String(const std::u16string\&) yapıcı

[String](../)'ı utf16 dizisinden oluşturur.

```cpp
System::String::String(const std::u16string &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const std::u16string\& | [String](../) içine dönüştürmek için Utf16 dize. |

## String::String(const std::string\&) yapıcı

UTF-8 biçiminde sunulan std::string dizisinden [String](../) oluşturur.

```cpp
System::String::String(const std::string &utf8str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| utf8str | const std::string\& | [String](../) içine dönüştürmek için std::string dizesi. |

## String::String(const std::u32string\&) yapıcı

[String](../)'ı std::u32string dizisinden oluşturur.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| u32str | const std::u32string\& | [String](../) içine dönüştürmek için std::u32string dizesi. |

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../arrayptr/)
* Sınıf [String](../)
* Sınıf [ReadOnlySpan](../../readonlyspan/)
* Yapı [IsStringLiteral](../../isstringliteral/)
* Yapı [IsStringPointer](../../isstringpointer/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)