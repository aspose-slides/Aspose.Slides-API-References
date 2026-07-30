---
title: Guid()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří objekt, který představuje GUID složený ze všech nul.
type: docs
weight: 1
url: /cs/system/guid/guid/
---
## Guid::Guid() konstruktor

Vytvoří objekt, který představuje GUID složený ze všech nul.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) konstruktor

Vytvoří objekt, který představuje GUID určený jako pole 8-bitových bezznakových celočíselných hodnot.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů obsahující jednotlivé bajty GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Vytvoří objekt, který představuje GUID určený jako pohled na pole 8-bitových bezznakových celočíselných hodnot.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Pole bajtů obsahující jednotlivé bajty GUID |

## Guid::Guid(const String\&) konstruktor

Vytvoří objekt, který představuje GUID určený jako řetězec.

```cpp
System::Guid::Guid(const String &g)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| g | const [String](../../string/)\& | Řetězcová reprezentace GUID, kterou bude objekt představovat |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) konstruktor

Vytvoří instanci třídy [Guid](../) z daných komponent GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | **int32_t** | Bity 0-31 GUID |
| b | **int16_t** | Bity 32-47 GUID |
| c | **int16_t** | Bity 48-63 GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů obsahující bity 64-127 GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Vytvoří instanci třídy [Guid](../) z daných komponent GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | **int32_t** | Bity 0-31 GUID |
| b | **int16_t** | Bity 32-47 GUID |
| c | **int16_t** | Bity 48-63 GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole bajtů obsahující bity 64-127 GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Vytvoří instanci třídy [Guid](../) z daných bezznakových celých čísel a bajtů.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | **int32_t** | Bity 0-31 GUID |
| b | **int16_t** | Bity 32-47 GUID |
| c | **int16_t** | Bity 48-63 GUID |
| d | **uint8_t** | Bity 64-71 GUID |
| e | **uint8_t** | Bity 72-79 GUID |
| f | **uint8_t** | Bity 80-87 GUID |
| g | **uint8_t** | Bity 88-95 GUID |
| h | **uint8_t** | Bity 96-103 GUID |
| i | **uint8_t** | Bity 104-111 GUID |
| j | **uint8_t** | Bity 112-119 GUID |
| k | **uint8_t** | Bity 120-127 GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Vytvoří instanci třídy [Guid](../) z daných bezznakových celých čísel a bajtů.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | **uint32_t** | Bity 0-31 GUID |
| b | **uint16_t** | Bity 32-47 GUID |
| c | **uint16_t** | Bity 48-63 GUID |
| d | **uint8_t** | Bity 64-71 GUID |
| e | **uint8_t** | Bity 72-79 GUID |
| f | **uint8_t** | Bity 80-87 GUID |
| g | **uint8_t** | Bity 88-95 GUID |
| h | **uint8_t** | Bity 96-103 GUID |
| i | **uint8_t** | Bity 104-111 GUID |
| j | **uint8_t** | Bity 112-119 GUID |
| k | **uint8_t** | Bity 120-127 GUID |

## Guid::Guid(const Guid\&) konstruktor

Vytvoří objekt, který představuje stejný GUID jako zadaný objekt.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| guid | const [Guid](../)\& | Objekt [Guid](../), ze kterého se kopíruje hodnota GUID |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [Guid](../)
* Třída [String](../../string/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)