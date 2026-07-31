---
title: ToDateTime()
second_title: Referensi API Aspose.Slides untuk C++
description: Konversi tidak didukung. Selalu melempar InvalidCastException.
type: docs
weight: 248
url: /id/system/convert/todatetime/
---
## Convert::ToDateTime(bool) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) metode


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) metode


Returns the specified date and time.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) metode


Converts the specified string to an instance of [DateTime](../../datetime/) class.

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembalian

Instance dari kelas [DateTime](../../datetime/) yang mewakili informasi tanggal dan waktu yang diwakili oleh string yang diberikan

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Converts the specified string to an instance of [DateTime](../../datetime/) class using the provided formatting information.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Instance dari kelas [DateTime](../../datetime/) yang mewakili informasi tanggal dan waktu yang diwakili oleh string yang diberikan

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metode




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) metode




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode


Converts the specified boxed value to equivalent [DateTime](../../datetime/) value.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Shared pointer ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai terkotak adalah [String](../../string/) |

### Nilai Kembalian

Nilai [DateTime](../../datetime/) yang setara dengan nilai terkotak yang diberikan

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [DateTime](../../datetime/)
* Kelas [Decimal](../../decimal/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Kelas [Object](../../object/)
* Struct [Convert](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)