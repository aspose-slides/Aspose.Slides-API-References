---
title: ToInt16()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan ke integer bertanda 16-bit yang setara.
type: docs
weight: 131
url: /id/system/convert/toint16/
---
## Convert::ToInt16(bool) metode

Mengonversi nilai boolean yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) metode

Mengonversi integer tak bertanda 8-bit yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) metode

Mengonversi integer bertanda 8-bit yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) metode

Mengonversi integer tak bertanda 16-bit yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) metode

Mengembalikan integer bertanda 16-bit yang ditentukan.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) metode

Mengonversi integer tak bertanda 32-bit yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) metode

Mengonversi integer bertanda 32-bit yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) metode

Mengonversi integer tak bertanda 64-bit yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) metode

Mengonversi integer bertanda 64-bit yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) metode

Mengonversi angka float yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) metode

Mengonversi angka double yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) metode

Mengonversi angka desimal yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) metode

Mengonversi karakter unicode yang ditentukan ke integer bertanda 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) metode

Mengonversi null-string yang ditentukan ke nilai integer 16-bit yang setara.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Nilai Kembalian

Nol.

## Convert::ToInt16(const char_t *) metode


Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembalian

Nilai integer 16-bit yang sama dengan angka yang direpresentasikan oleh c-string yang ditentukan

## Convert::ToInt16(const String\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |

### Nilai Kembalian

Nilai integer 16-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt16(const String\&, int) metode


Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| from_base | int | basis angka yang direpresentasikan oleh string |

### Nilai Kembalian

Nilai integer 16-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 16-bit yang setara menggunakan informasi format yang disediakan.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | pointer ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer 16-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) metode




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 16-bit yang setara menggunakan informasi format yang disediakan dan gaya angka.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string angka |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | pointer ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer 16-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) metode 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) metode 




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi nilai yang dibungkus (boxed) yang ditentukan ke nilai integer 16-bit yang setara.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | pointer bersama ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembalian

Nilai integer 16-bit yang setara dengan nilai yang dibungkus yang ditentukan

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)