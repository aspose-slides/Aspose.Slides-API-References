---
title: ToChar()
second_title: Referensi API Aspose.Slides untuk C++
description: Konversi tidak didukung. Selalu melempar InvalidCastException.
type: docs
weight: 118
url: /id/system/convert/tochar/
---
## Convert::ToChar(bool) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) metode


Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) metode


Mengonversi bilangan bulat bertanda 8-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) metode


Mengonversi bilangan bulat tak bertanda 16-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) metode


Mengonversi bilangan bulat bertanda 16-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) metode


Mengonversi bilangan bulat tak bertanda 32-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) metode


Mengonversi bilangan bulat bertanda 32-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) metode


Mengonversi bilangan bulat tak bertanda 64-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) metode


Mengonversi bilangan bulat bertanda 64-bit yang ditentukan menjadi karakter unicode yang setara.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) metode


Mengembalikan karakter unicode yang ditentukan.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) metode


Mengonversi karakter pertama dan satu-satunya dari c-string yang ditentukan menjadi nilai char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi; diharapkan bahwa c-string memiliki panjang tepat 1 karakter. |

### Nilai Kembali

Karakter pertama dan satu-satunya dari c-string yang ditentukan jika panjangnya tepat 1 karakter, jika tidak - 0

## Convert::ToChar(const String\&) metode


Mengonversi karakter pertama dan satu-satunya dari string yang ditentukan menjadi nilai char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi; diharapkan bahwa string memiliki panjang tepat 1 karakter. |

### Nilai Kembali

Karakter pertama dan satu-satunya dari string yang ditentukan jika panjangnya tepat 1 karakter, jika tidak - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi karakter pertama dan satu-satunya dari string yang ditentukan menjadi nilai char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi; diharapkan bahwa string memiliki panjang tepat 1 karakter. |

### Nilai Kembali

Karakter pertama dan satu-satunya dari string yang ditentukan jika panjangnya tepat 1 karakter, jika tidak - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi nilai yang dibungkus menjadi karakter unicode yang setara.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Shared pointer ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembali

Karakter unicode yang setara dengan nilai yang dibungkus yang ditentukan

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Decimal](../../decimal/)
* Kelas [DateTime](../../datetime/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [Object](../../object/)
* Struktur [Convert](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)