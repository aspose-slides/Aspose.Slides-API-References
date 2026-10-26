---
title: Guid()
second_title: Aspose.Slides for C++ API referencia
description: Létrehoz egy objektumot, amely egy minden nullából álló GUID-et képvisel.
type: docs
weight: 1
url: /hu/system/guid/guid/
---
## Guid::Guid() konstruktor

Létrehoz egy objektumot, amely egy minden nullából álló GUID-et képvisel.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) konstruktor

Létrehoz egy objektumot, amely egy olyan GUID-et képvisel, amelyet egy 8 bites előjel nélküli egész értékekből álló tömb határoz meg.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Egy bájt-tömb, amely a GUID különálló bájtjait tartalmazza |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Létrehoz egy objektumot, amely egy olyan GUID-et képvisel, amelyet egy 8 bites előjel nélküli egész értékek tömbnézete határoz meg.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Egy bájt-tömb, amely a GUID különálló bájtjait tartalmazza |

## Guid::Guid(const String\&) konstruktor

Létrehoz egy objektumot, amely egy karakterláncként megadott GUID-et képvisel.

```cpp
System::Guid::Guid(const String &g)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| g | const [String](../../string/)\& | A GUID karakterlánc ábrázolása, amelyet a létrehozott objektum képvisel |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) konstruktor

Létrehoz egy példányt a [Guid](../) osztályból a megadott GUID komponensekből.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | **int32_t** | A GUID 0-31. bite |
| b | **int16_t** | A GUID 32-47. bite |
| c | **int16_t** | A GUID 48-63. bite |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Egy bájt-tömb, amely a GUID 64-127. bitjeit tartalmazza |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Létrehoz egy példányt a [Guid](../) osztályból a megadott GUID komponensekből.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | **int32_t** | A GUID 0-31. bite |
| b | **int16_t** | A GUID 32-47. bite |
| c | **int16_t** | A GUID 48-63. bite |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Egy bájt-tömb nézet, amely a GUID 64-127. bitjeit tartalmazza |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Létrehoz egy példányt a [Guid](../) osztályból a megadott előjel nélküli egész számokból és bájtokból.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | **int32_t** | A GUID 0-31. bite |
| b | **int16_t** | A GUID 32-47. bite |
| c | **int16_t** | A GUID 48-63. bite |
| d | **uint8_t** | A GUID 64-71. bite |
| e | **uint8_t** | A GUID 72-79. bite |
| f | **uint8_t** | A GUID 80-87. bite |
| g | **uint8_t** | A GUID 88-95. bite |
| h | **uint8_t** | A GUID 96-103. bite |
| i | **uint8_t** | A GUID 104-111. bite |
| j | **uint8_t** | A GUID 112-119. bite |
| k | **uint8_t** | A GUID 120-127. bite |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Létrehoz egy példányt a [Guid](../) osztályból a megadott előjel nélküli egész számokból és bájtokból.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | **uint32_t** | A GUID 0-31. bite |
| b | **uint16_t** | A GUID 32-47. bite |
| c | **uint16_t** | A GUID 48-63. bite |
| d | **uint8_t** | A GUID 64-71. bite |
| e | **uint8_t** | A GUID 72-79. bite |
| f | **uint8_t** | A GUID 80-87. bite |
| g | **uint8_t** | A GUID 88-95. bite |
| h | **uint8_t** | A GUID 96-103. bite |
| i | **uint8_t** | A GUID 104-111. bite |
| j | **uint8_t** | A GUID 112-119. bite |
| k | **uint8_t** | A GUID 120-127. bite |

## Guid::Guid(const Guid\&) konstruktor

Létrehoz egy objektumot, amely ugyanazt a GUID-et képviseli, mint a megadott objektum.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| guid | const [Guid](../)\& | A [Guid](../) objektum, amelyből a GUID értéket másolni kell |

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [Guid](../)
* Osztály [String](../../string/)
* Névterület [System](../../)
* Library [Aspose.Slides](../../../)