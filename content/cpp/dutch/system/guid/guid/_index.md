---
title: Guid()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een object dat een GUID vertegenwoordigt die uitsluitend uit nullen bestaat.
type: docs
weight: 1
url: /nl/system/guid/guid/
---
## Guid::Guid() constructor

Construeert een object dat een GUID vertegenwoordigt die uitsluitend uit nullen bestaat.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) constructor

Construeert een object dat een GUID weergeeft die is gespecificeerd als een array van onondertekende 8-bit gehele getallen.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Een byte-array die afzonderlijke bytes van de GUID bevat. |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) constructor

Construeert een object dat een GUID weergeeft die is gespecificeerd als een array-view van onondertekende 8-bit gehele getallen.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Een byte-array die afzonderlijke bytes van de GUID bevat. |

## Guid::Guid(const String\&) constructor

Construeert een object dat een GUID weergeeft die is gespecificeerd als een tekenreeks.

```cpp
System::Guid::Guid(const String &g)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| g | const [String](../../string/)\& | De tekenreeksrepresentatie van een GUID die door het te construeren object moet worden weergegeven. |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) constructor

Construeert een instantie van de klasse [Guid](../) met de opgegeven GUID-componenten.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 van de GUID |
| b | **int16_t** | Bits 32-47 van de GUID |
| c | **int16_t** | Bits 48-63 van de GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Een byte-array die bits 64-127 van de GUID bevat. |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) constructor

Construeert een instantie van de klasse [Guid](../) met de opgegeven GUID-componenten.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 van de GUID |
| b | **int16_t** | Bits 32-47 van de GUID |
| c | **int16_t** | Bits 48-63 van de GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Een byte-array-view die bits 64-127 van de GUID bevat. |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor

Construeert een instantie van de klasse [Guid](../) met de opgegeven onondertekende gehele getallen en bytes.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 van de GUID |
| b | **int16_t** | Bits 32-47 van de GUID |
| c | **int16_t** | Bits 48-63 van de GUID |
| d | **uint8_t** | Bits 64-71 van de GUID |
| e | **uint8_t** | Bits 72-79 van de GUID |
| f | **uint8_t** | Bits 80-87 van de GUID |
| g | **uint8_t** | Bits 88-95 van de GUID |
| h | **uint8_t** | Bits 96-103 van de GUID |
| i | **uint8_t** | Bits 104-111 van de GUID |
| j | **uint8_t** | Bits 112-119 van de GUID |
| k | **uint8_t** | Bits 120-127 van de GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor

Construeert een instantie van de klasse [Guid](../) met de opgegeven onondertekende gehele getallen en bytes.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | **uint32_t** | Bits 0-31 van de GUID |
| b | **uint16_t** | Bits 32-47 van de GUID |
| c | **uint16_t** | Bits 48-63 van de GUID |
| d | **uint8_t** | Bits 64-71 van de GUID |
| e | **uint8_t** | Bits 72-79 van de GUID |
| f | **uint8_t** | Bits 80-87 van de GUID |
| g | **uint8_t** | Bits 88-95 van de GUID |
| h | **uint8_t** | Bits 96-103 van de GUID |
| i | **uint8_t** | Bits 104-111 van de GUID |
| j | **uint8_t** | Bits 112-119 van de GUID |
| k | **uint8_t** | Bits 120-127 van de GUID |

## Guid::Guid(const Guid\&) constructor

Construeert een object dat dezelfde GUID vertegenwoordigt als het opgegeven object.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| guid | const [Guid](../)\& | Het [Guid](../)-object waarvan de GUID-waarde moet worden gekopieerd. |

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Guid](../)
* Klasse [String](../../string/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)