---
title: Guid()
second_title: Aspose.Slides for C++ API Referansı
description: Tüm sıfırlardan oluşan bir GUID temsil eden bir nesne oluşturur.
type: docs
weight: 1
url: /tr/system/guid/guid/
---
## Guid::Guid() yapıcı

Tüm sıfırlardan oluşan bir GUID temsil eden bir nesne oluşturur.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) yapıcı

İmzasız 8-bit tamsayı değerleri dizisi olarak belirtilen bir GUID temsil eden bir nesne oluşturur.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID'in ayrı baytlarını içeren bir bayt dizisi |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) yapıcı

İmzasız 8-bit tamsayı değerlerinin dizi görünümü olarak belirtilen bir GUID temsil eden bir nesne oluşturur.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | GUID'in ayrı baytlarını içeren bir bayt dizisi |

## Guid::Guid(const String\&) yapıcı

Bir dize olarak belirtilen bir GUID temsil eden bir nesne oluşturur.

```cpp
System::Guid::Guid(const String &g)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g | const [String](../../string/)\& | Oluşturulan nesnenin temsil edeceği GUID'in dize temsili |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) yapıcı

Belirtilen GUID bileşenlerinden [Guid](../) sınıfının bir örneğini oluşturur.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | **int32_t** | GUID'in 0-31 bitleri |
| b | **int16_t** | GUID'in 32-47 bitleri |
| c | **int16_t** | GUID'in 48-63 bitleri |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID'in 64-127 bitlerini içeren bir bayt dizisi |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) yapıcı

Belirtilen GUID bileşenlerinden [Guid](../) sınıfının bir örneğini oluşturur.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | **int32_t** | GUID'in 0-31 bitleri |
| b | **int16_t** | GUID'in 32-47 bitleri |
| c | **int16_t** | GUID'in 48-63 bitleri |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | GUID'in 64-127 bitlerini içeren bir bayt dizi görünümü |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) yapıcı

Belirtilen imzasız tamsayılar ve baytlardan [Guid](../) sınıfının bir örneğini oluşturur.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | **int32_t** | GUID'in 0-31 bitleri |
| b | **int16_t** | GUID'in 32-47 bitleri |
| c | **int16_t** | GUID'in 48-63 bitleri |
| d | **uint8_t** | GUID'in 64-71 bitleri |
| e | **uint8_t** | GUID'in 72-79 bitleri |
| f | **uint8_t** | GUID'in 80-87 bitleri |
| g | **uint8_t** | GUID'in 88-95 bitleri |
| h | **uint8_t** | GUID'in 96-103 bitleri |
| i | **uint8_t** | GUID'in 104-111 bitleri |
| j | **uint8_t** | GUID'in 112-119 bitleri |
| k | **uint8_t** | GUID'in 120-127 bitleri |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) yapıcı

Belirtilen imzasız tamsayılar ve baytlardan [Guid](../) sınıfının bir örneğini oluşturur.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | **uint32_t** | GUID'in 0-31 bitleri |
| b | **uint16_t** | GUID'in 32-47 bitleri |
| c | **uint16_t** | GUID'in 48-63 bitleri |
| d | **uint8_t** | GUID'in 64-71 bitleri |
| e | **uint8_t** | GUID'in 72-79 bitleri |
| f | **uint8_t** | GUID'in 80-87 bitleri |
| g | **uint8_t** | GUID'in 88-95 bitleri |
| h | **uint8_t** | GUID'in 96-103 bitleri |
| i | **uint8_t** | GUID'in 104-111 bitleri |
| j | **uint8_t** | GUID'in 112-119 bitleri |
| k | **uint8_t** | GUID'in 120-127 bitleri |

## Guid::Guid(const Guid\&) yapıcı

Belirtilen nesneyle aynı GUID'i temsil eden bir nesne oluşturur.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| guid | const [Guid](../)\& | GUID değerini kopyalanacak [Guid](../) nesnesi |

## Diğerlerine Bak

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [Guid](../)
* Sınıf [String](../../string/)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)