---
title: Write()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen nesnenin dize temsilini standart çıkış akışına yazar.
type: docs
weight: 1
url: /tr/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) metodu


Belirtilen nesnenin dize temsilini standart çıkış akışına yazar.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Çıktı verilecek nesnenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) çıktısı |

## Console::Write(bool) metodu


Bool değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(bool value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **bool** | Çıktı verilecek değer |

## Console::Write(char_t) metodu


Belirtilen karakter değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(char_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char_t | Çıktı verilecek değer |

## Console::Write(const ArrayPtr\<char_t\>\&) metodu


Belirtilen karakter dizisinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Çıktı verilecek dizi |

## Console::Write(const Decimal\&) metodu


[Decimal](../../decimal/) değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Çıktı verilecek değer |

## Console::Write(double) metodu


Double hassasiyetli kayan nokta değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(double value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Çıktı verilecek değer |

## Console::Write(float) metodu


Single hassasiyetli kayan nokta değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(float value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **float** | Çıktı verilecek değer |

## Console::Write(int32_t) metodu


32 bit tamsayı değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(int32_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **int32_t** | Çıktı verilecek değer |

## Console::Write(int64_t) metodu


64 bit tamsayı değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(int64_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **int64_t** | Çıktı verilecek değer |

## Console::Write(const String\&) metodu


Belirtilen string nesnesinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Çıktı verilecek string nesnesi |

## Console::Write(const char_t *) metodu


Belirtilen C dizesinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Çıktı verilecek C dizesi |

## Console::Write(const TypeInfo\&) metodu


[TypeInfo](../../typeinfo/) değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Çıktı verilecek değer |

## Console::Write(uint32_t) metodu


İmzasız 32 bit tamsayı değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(uint32_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint32_t** | Çıktı verilecek değer |

## Console::Write(uint64_t) metodu


İmzasız 64 bit tamsayı değerinin dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(uint64_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint64_t** | Çıktı verilecek değer |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodu


Belirtilen karakter dizisinin belirtilen aralığının dize temsilini standart çıkış akışına yazar.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Karakter dizisi |
| index | **int32_t** | Çıktı verilecek aralığın başlangıç dizini |
| count | **int32_t** | Çıktı verilecek aralıktaki öğe sayısı |

## Console::Write(const String\&, Args\&&...) metodu


Belirtilen argümanların, belirtilen biçime göre biçimlendirilmiş dize temsilini standart çıkış akışına yazar.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | Çıktı verilecek değerlerin türleri |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../string/)\& | Dize biçimi |
| args | Args\&&... | Çıktı verilecek değerler |

## Console::Write(const char *) metodu




```cpp
static void System::Console::Write(const char *)=delete
```

## İlgili Bağlantılar

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)