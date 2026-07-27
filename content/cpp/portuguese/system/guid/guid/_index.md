---
title: Guid()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um objeto que representa um GUID composto por todos os zeros.
type: docs
weight: 1
url: /pt/system/guid/guid/
---
## Guid::Guid() construtor

Constrói um objeto que representa um GUID composto por todos os zeros.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) construtor

Constrói um objeto que representa um GUID especificado como um array de valores inteiros sem sinal de 8 bits.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Um array de bytes contendo os bytes individuais do GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) construtor

Constrói um objeto que representa um GUID especificado como uma visualização de array de valores inteiros sem sinal de 8 bits.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Um array de bytes contendo os bytes individuais do GUID |

## Guid::Guid(const String\&) construtor

Constrói um objeto que representa um GUID especificado como uma string.

```cpp
System::Guid::Guid(const String &g)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| g | const [String](../../string/)\& | A representação em string de um GUID a ser representado pelo objeto sendo construído |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) construtor

Constrói uma instância da classe [Guid](../) a partir dos componentes GUID especificados.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 do GUID |
| b | **int16_t** | Bits 32-47 do GUID |
| c | **int16_t** | Bits 48-63 do GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Um array de bytes contendo os bits 64-127 do GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) construtor

Constrói uma instância da classe [Guid](../) a partir dos componentes GUID especificados.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 do GUID |
| b | **int16_t** | Bits 32-47 do GUID |
| c | **int16_t** | Bits 48-63 do GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Uma visualização de array de bytes contendo os bits 64-127 do GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) construtor

Constrói uma instância da classe [Guid](../) a partir dos inteiros sem sinal e bytes especificados.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 do GUID |
| b | **int16_t** | Bits 32-47 do GUID |
| c | **int16_t** | Bits 48-63 do GUID |
| d | **uint8_t** | Bits 64-71 do GUID |
| e | **uint8_t** | Bits 72-79 do GUID |
| f | **uint8_t** | Bits 80-87 do GUID |
| g | **uint8_t** | Bits 88-95 do GUID |
| h | **uint8_t** | Bits 96-103 do GUID |
| i | **uint8_t** | Bits 104-111 do GUID |
| j | **uint8_t** | Bits 112-119 do GUID |
| k | **uint8_t** | Bits 120-127 do GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) construtor

Constrói uma instância da classe [Guid](../) a partir dos inteiros sem sinal e bytes especificados.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | **uint32_t** | Bits 0-31 do GUID |
| b | **uint16_t** | Bits 32-47 do GUID |
| c | **uint16_t** | Bits 48-63 do GUID |
| d | **uint8_t** | Bits 64-71 do GUID |
| e | **uint8_t** | Bits 72-79 do GUID |
| f | **uint8_t** | Bits 80-87 do GUID |
| g | **uint8_t** | Bits 88-95 do GUID |
| h | **uint8_t** | Bits 96-103 do GUID |
| i | **uint8_t** | Bits 104-111 do GUID |
| j | **uint8_t** | Bits 112-119 do GUID |
| k | **uint8_t** | Bits 120-127 do GUID |

## Guid::Guid(const Guid\&) construtor

Constrói um objeto que representa o mesmo GUID do objeto especificado.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| guid | const [Guid](../)\& | O objeto [Guid](../) do qual copiar o valor do GUID |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Guid](../)
* Classe [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)