---
title: Guid()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Objekt, das eine GUID darstellt, die ausschließlich aus Nullen besteht.
type: docs
weight: 1
url: /de/system/guid/guid/
---
## Guid::Guid() Konstruktor

Erstellt ein Objekt, das eine GUID darstellt, die ausschließlich aus Nullen besteht.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) Konstruktor

Erstellt ein Objekt, das eine GUID darstellt, die als Array von vorzeichenlosen 8-Bit-Ganzzahlen angegeben ist.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ein Byte-Array, das die einzelnen Bytes der GUID enthält |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) Konstruktor

Erstellt ein Objekt, das eine GUID darstellt, die als Array-Ansicht von vorzeichenlosen 8-Bit-Ganzzahlen angegeben ist.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Ein Byte-Array, das die einzelnen Bytes der GUID enthält |

## Guid::Guid(const String\&) Konstruktor

Erstellt ein Objekt, das eine GUID darstellt, die als Zeichenkette angegeben ist.

```cpp
System::Guid::Guid(const String &g)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | const [String](../../string/)\& | Die Zeichenkettenrepräsentation einer GUID, die vom zu erstellenden Objekt dargestellt wird |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) Konstruktor

Erstellt eine Instanz der Klasse [Guid](../) aus den angegebenen GUID-Komponenten.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 der GUID |
| b | **int16_t** | Bits 32-47 der GUID |
| c | **int16_t** | Bits 48-63 der GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ein Byte-Array, das die Bits 64-127 der GUID enthält |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) Konstruktor

Erstellt eine Instanz der Klasse [Guid](../) aus den angegebenen GUID-Komponenten.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 der GUID |
| b | **int16_t** | Bits 32-47 der GUID |
| c | **int16_t** | Bits 48-63 der GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Eine Byte-Array-Ansicht, die die Bits 64-127 der GUID enthält |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) Konstruktor

Erstellt eine Instanz der Klasse [Guid](../) aus den angegebenen vorzeichenlosen Ganzzahlen und Bytes.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 der GUID |
| b | **int16_t** | Bits 32-47 der GUID |
| c | **int16_t** | Bits 48-63 der GUID |
| d | **uint8_t** | Bits 64-71 der GUID |
| e | **uint8_t** | Bits 72-79 der GUID |
| f | **uint8_t** | Bits 80-87 der GUID |
| g | **uint8_t** | Bits 88-95 der GUID |
| h | **uint8_t** | Bits 96-103 der GUID |
| i | **uint8_t** | Bits 104-111 der GUID |
| j | **uint8_t** | Bits 112-119 der GUID |
| k | **uint8_t** | Bits 120-127 der GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) Konstruktor

Erstellt eine Instanz der Klasse [Guid](../) aus den angegebenen vorzeichenlosen Ganzzahlen und Bytes.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | **uint32_t** | Bits 0-31 der GUID |
| b | **uint16_t** | Bits 32-47 der GUID |
| c | **uint16_t** | Bits 48-63 der GUID |
| d | **uint8_t** | Bits 64-71 der GUID |
| e | **uint8_t** | Bits 72-79 der GUID |
| f | **uint8_t** | Bits 80-87 der GUID |
| g | **uint8_t** | Bits 88-95 der GUID |
| h | **uint8_t** | Bits 96-103 der GUID |
| i | **uint8_t** | Bits 104-111 der GUID |
| j | **uint8_t** | Bits 112-119 der GUID |
| k | **uint8_t** | Bits 120-127 der GUID |

## Guid::Guid(const Guid\&) Konstruktor

Erstellt ein Objekt, das dieselbe GUID wie das angegebene Objekt darstellt.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| guid | const [Guid](../)\& | Das [Guid](../)-Objekt, aus dem der GUID-Wert kopiert wird |

## Siehe Auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Guid](../)
* Klasse [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)