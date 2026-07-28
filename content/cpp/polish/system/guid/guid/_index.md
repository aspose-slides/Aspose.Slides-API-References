---
title: Guid()
second_title: Aspose.Slides for C++ - referencja API
description: Tworzy obiekt reprezentujący GUID składający się wyłącznie z zer.
type: docs
weight: 1
url: /pl/system/guid/guid/
---
## Guid::Guid() konstruktor

Tworzy obiekt reprezentujący GUID składający się wyłącznie z zer.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) konstruktor

Tworzy obiekt reprezentujący GUID określony jako tablica wartości całkowitych bez znaku 8-bitowych.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów zawierająca poszczególne bajty GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Tworzy obiekt reprezentujący GUID określony jako widok tablicy wartości całkowitych bez znaku 8-bitowych.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Tablica bajtów zawierająca poszczególne bajty GUID |

## Guid::Guid(const String\&) konstruktor

Tworzy obiekt reprezentujący GUID określony jako ciąg znaków.

```cpp
System::Guid::Guid(const String &g)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| g | const [String](../../string/)\& | Reprezentacja ciągowa GUID, która ma być reprezentowana przez tworzony obiekt |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) konstruktor

Tworzy instancję klasy [Guid](../) na podstawie określonych składników GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | **int32_t** | Bity 0-31 GUID-a |
| b | **int16_t** | Bity 32-47 GUID-a |
| c | **int16_t** | Bity 48-63 GUID-a |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Tablica bajtów zawierająca bity 64-127 GUID-a |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Tworzy instancję klasy [Guid](../) na podstawie określonych składników GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | **int32_t** | Bity 0-31 GUID-a |
| b | **int16_t** | Bity 32-47 GUID-a |
| c | **int16_t** | Bity 48-63 GUID-a |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy bajtów zawierający bity 64-127 GUID-a |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Tworzy instancję klasy [Guid](../) na podstawie określonych liczb całkowitych bez znaku i bajtów.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | **int32_t** | Bity 0-31 GUID-a |
| b | **int16_t** | Bity 32-47 GUID-a |
| c | **int16_t** | Bity 48-63 GUID-a |
| d | **uint8_t** | Bity 64-71 GUID-a |
| e | **uint8_t** | Bity 72-79 GUID-a |
| f | **uint8_t** | Bity 80-87 GUID-a |
| g | **uint8_t** | Bity 88-95 GUID-a |
| h | **uint8_t** | Bity 96-103 GUID-a |
| i | **uint8_t** | Bity 104-111 GUID-a |
| j | **uint8_t** | Bity 112-119 GUID-a |
| k | **uint8_t** | Bity 120-127 GUID-a |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Tworzy instancję klasy [Guid](../) na podstawie określonych liczb całkowitych bez znaku i bajtów.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | **uint32_t** | Bity 0-31 GUID-a |
| b | **uint16_t** | Bity 32-47 GUID-a |
| c | **uint16_t** | Bity 48-63 GUID-a |
| d | **uint8_t** | Bity 64-71 GUID-a |
| e | **uint8_t** | Bity 72-79 GUID-a |
| f | **uint8_t** | Bity 80-87 GUID-a |
| g | **uint8_t** | Bity 88-95 GUID-a |
| h | **uint8_t** | Bity 96-103 GUID-a |
| i | **uint8_t** | Bity 104-111 GUID-a |
| j | **uint8_t** | Bity 112-119 GUID-a |
| k | **uint8_t** | Bity 120-127 GUID-a |

## Guid::Guid(const Guid\&) konstruktor

Tworzy obiekt, który reprezentuje ten sam GUID co określony obiekt.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| guid | const [Guid](../)\& | Obiekt [Guid](../), z którego kopiowana jest wartość GUID |

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [Guid](../)
* Klasa [String](../../string/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)