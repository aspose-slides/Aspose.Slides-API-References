---
title: Guid()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un objet qui représente un GUID composé uniquement de zéros.
type: docs
weight: 1
url: /fr/system/guid/guid/
---
## Guid::Guid() constructeur

Construit un objet qui représente un GUID composé de zéros.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) constructeur

Construit un objet qui représente un GUID spécifié sous forme de tableau de valeurs entières non signées de 8 bits.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Un tableau d'octets contenant les octets séparés du GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) constructeur

Construit un objet qui représente un GUID spécifié sous forme de vue sur un tableau de valeurs entières non signées de 8 bits.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Une vue de tableau contenant les octets séparés du GUID |

## Guid::Guid(const String\&) constructeur

Construit un objet qui représente un GUID spécifié sous forme de chaîne.

```cpp
System::Guid::Guid(const String &g)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| g | const [String](../../string/)\& | La représentation sous forme de chaîne d'un GUID à représenter par l'objet en cours de construction |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) constructeur

Construit une instance de la classe [Guid](../) à partir des composants de GUID spécifiés.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 du GUID |
| b | **int16_t** | Bits 32-47 du GUID |
| c | **int16_t** | Bits 48-63 du GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Un tableau d'octets contenant les bits 64-127 du GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) constructeur

Construit une instance de la classe [Guid](../) à partir des composants de GUID spécifiés.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 du GUID |
| b | **int16_t** | Bits 32-47 du GUID |
| c | **int16_t** | Bits 48-63 du GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Une vue sur un tableau d'octets contenant les bits 64-127 du GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructeur

Construit une instance de la classe [Guid](../) à partir des entiers non signés et des octets spécifiés.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 du GUID |
| b | **int16_t** | Bits 32-47 du GUID |
| c | **int16_t** | Bits 48-63 du GUID |
| d | **uint8_t** | Bits 64-71 du GUID |
| e | **uint8_t** | Bits 72-79 du GUID |
| f | **uint8_t** | Bits 80-87 du GUID |
| g | **uint8_t** | Bits 88-95 du GUID |
| h | **uint8_t** | Bits 96-103 du GUID |
| i | **uint8_t** | Bits 104-111 du GUID |
| j | **uint8_t** | Bits 112-119 du GUID |
| k | **uint8_t** | Bits 120-127 du GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructeur

Construit une instance de la classe [Guid](../) à partir des entiers non signés et des octets spécifiés.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | **uint32_t** | Bits 0-31 du GUID |
| b | **uint16_t** | Bits 32-47 du GUID |
| c | **uint16_t** | Bits 48-63 du GUID |
| d | **uint8_t** | Bits 64-71 du GUID |
| e | **uint8_t** | Bits 72-79 du GUID |
| f | **uint8_t** | Bits 80-87 du GUID |
| g | **uint8_t** | Bits 88-95 du GUID |
| h | **uint8_t** | Bits 96-103 du GUID |
| i | **uint8_t** | Bits 104-111 du GUID |
| j | **uint8_t** | Bits 112-119 du GUID |
| k | **uint8_t** | Bits 120-127 du GUID |

## Guid::Guid(const Guid\&) constructeur

Construit un objet qui représente le même GUID que l'objet spécifié.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| guid | const [Guid](../)\& | L'objet [Guid](../) à partir duquel copier la valeur du GUID |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Guid](../)
* Classe [String](../../string/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)