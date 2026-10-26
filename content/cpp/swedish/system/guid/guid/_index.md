---
title: Guid()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett objekt som representerar ett GUID bestående av enbart nollor.
type: docs
weight: 1
url: /sv/system/guid/guid/
---
## Guid::Guid() konstruktor


Skapar ett objekt som representerar ett GUID bestående av enbart nollor.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) konstruktor


Skapar ett objekt som representerar ett GUID specificerat som en array av osignerade 8-bitars heltal.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | En byte-array som innehåller separata bytevärden för GUID:et |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) konstruktor


Skapar ett objekt som representerar ett GUID specificerat som en array-vy av osignerade 8-bitars heltal.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | En byte-array-vy som innehåller separata bytevärden för GUID:et |

## Guid::Guid(const String\&) konstruktor


Skapar ett objekt som representerar ett GUID angivet som en sträng.

```cpp
System::Guid::Guid(const String &g)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | const [String](../../string/)\& | Strängrepresentationen av ett GUID som ska representeras av objektet som konstrueras |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) konstruktor


Skapar en instans av [Guid](../) klass från de specificerade GUID-komponenterna.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | **int32_t** | Bitarna 0-31 av GUID:et |
| b | **int16_t** | Bitarna 32-47 av GUID:et |
| c | **int16_t** | Bitarna 48-63 av GUID:et |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | En byte-array som innehåller bitarna 64-127 av GUID:et |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) konstruktor


Skapar en instans av [Guid](../) klass från de specificerade GUID-komponenterna.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | **int32_t** | Bitarna 0-31 av GUID:et |
| b | **int16_t** | Bitarna 32-47 av GUID:et |
| c | **int16_t** | Bitarna 48-63 av GUID:et |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | En byte-array-vy som innehåller bitarna 64-127 av GUID:et |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor


Skapar en instans av [Guid](../) klass från de specificerade osignerade heltalen och byten.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | **int32_t** | Bitarna 0-31 av GUID:et |
| b | **int16_t** | Bitarna 32-47 av GUID:et |
| c | **int16_t** | Bitarna 48-63 av GUID:et |
| d | **uint8_t** | Bitarna 64-71 av GUID:et |
| e | **uint8_t** | Bitarna 72-79 av GUID:et |
| f | **uint8_t** | Bitarna 80-87 av GUID:et |
| g | **uint8_t** | Bitarna 88-95 av GUID:et |
| h | **uint8_t** | Bitarna 96-103 av GUID:et |
| i | **uint8_t** | Bitarna 104-111 av GUID:et |
| j | **uint8_t** | Bitarna 112-119 av GUID:et |
| k | **uint8_t** | Bitarna 120-127 av GUID:et |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor


Skapar en instans av [Guid](../) klass från de specificerade osignerade heltalen och byten.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | **uint32_t** | Bitarna 0-31 av GUID:et |
| b | **uint16_t** | Bitarna 32-47 av GUID:et |
| c | **uint16_t** | Bitarna 48-63 av GUID:et |
| d | **uint8_t** | Bitarna 64-71 av GUID:et |
| e | **uint8_t** | Bitarna 72-79 av GUID:et |
| f | **uint8_t** | Bitarna 80-87 av GUID:et |
| g | **uint8_t** | Bitarna 88-95 av GUID:et |
| h | **uint8_t** | Bitarna 96-103 av GUID:et |
| i | **uint8_t** | Bitarna 104-111 av GUID:et |
| j | **uint8_t** | Bitarna 112-119 av GUID:et |
| k | **uint8_t** | Bitarna 120-127 av GUID:et |

## Guid::Guid(const Guid\&) konstruktor


Skapar ett objekt som representerar samma GUID som det angivna objektet.

```cpp
System::Guid::Guid(const Guid &guid)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | const [Guid](../)\& | [Guid](../)-objektet att kopiera GUID-värdet från |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [Guid](../)
* Klass [String](../../string/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)