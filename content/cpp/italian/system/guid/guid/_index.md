---
title: Guid()
second_title: Riferimento API di Aspose.Slides per C++ 
description: Costruisce un oggetto che rappresenta un GUID costituito interamente da zero.
type: docs
weight: 1
url: /it/system/guid/guid/
---
## Guid::Guid() costruttore

Costruisce un oggetto che rappresenta un GUID costituito interamente da zero.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) costruttore

Costruisce un oggetto che rappresenta un GUID specificato come array di valori interi senza segno a 8 bit.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Un array di byte contenente i byte separati del GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) costruttore

Costruisce un oggetto che rappresenta un GUID specificato come vista di un array di valori interi senza segno a 8 bit.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Una vista di array di byte contenente i byte separati del GUID |

## Guid::Guid(const String\&) costruttore

Costruisce un oggetto che rappresenta un GUID specificato come stringa.

```cpp
System::Guid::Guid(const String &g)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | const [String](../../string/)\& | La rappresentazione stringa di un GUID da rappresentare dall'oggetto in fase di costruzione |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) costruttore

Costruisce un'istanza della classe [Guid](../) dai componenti GUID specificati.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | **int32_t** | Bit 0-31 del GUID |
| b | **int16_t** | Bit 32-47 del GUID |
| c | **int16_t** | Bit 48-63 del GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Un array di byte contenente i bit 64-127 del GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) costruttore

Costruisce un'istanza della classe [Guid](../) dai componenti GUID specificati.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | **int32_t** | Bit 0-31 del GUID |
| b | **int16_t** | Bit 32-47 del GUID |
| c | **int16_t** | Bit 48-63 del GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Una vista di array di byte contenente i bit 64-127 del GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) costruttore

Costruisce un'istanza della classe [Guid](../) dagli interi senza segno e byte specificati.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | **int32_t** | Bit 0-31 del GUID |
| b | **int16_t** | Bit 32-47 del GUID |
| c | **int16_t** | Bit 48-63 del GUID |
| d | **uint8_t** | Bit 64-71 del GUID |
| e | **uint8_t** | Bit 72-79 del GUID |
| f | **uint8_t** | Bit 80-87 del GUID |
| g | **uint8_t** | Bit 88-95 del GUID |
| h | **uint8_t** | Bit 96-103 del GUID |
| i | **uint8_t** | Bit 104-111 del GUID |
| j | **uint8_t** | Bit 112-119 del GUID |
| k | **uint8_t** | Bit 120-127 del GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) costruttore

Costruisce un'istanza della classe [Guid](../) dagli interi senza segno e byte specificati.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | **uint32_t** | Bit 0-31 del GUID |
| b | **uint16_t** | Bit 32-47 del GUID |
| c | **uint16_t** | Bit 48-63 del GUID |
| d | **uint8_t** | Bit 64-71 del GUID |
| e | **uint8_t** | Bit 72-79 del GUID |
| f | **uint8_t** | Bit 80-87 del GUID |
| g | **uint8_t** | Bit 88-95 del GUID |
| h | **uint8_t** | Bit 96-103 del GUID |
| i | **uint8_t** | Bit 104-111 del GUID |
| j | **uint8_t** | Bit 112-119 del GUID |
| k | **uint8_t** | Bit 120-127 del GUID |

## Guid::Guid(const Guid\&) costruttore

Costruisce un oggetto che rappresenta lo stesso GUID dell'oggetto specificato.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| guid | const [Guid](../)\& | L'oggetto [Guid](../) da cui copiare il valore GUID |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Guid](../)
* Classe [String](../../string/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)