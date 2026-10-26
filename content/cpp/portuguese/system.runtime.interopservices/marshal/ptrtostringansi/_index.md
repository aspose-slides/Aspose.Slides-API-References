---
title: PtrToStringAnsi()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma String gerenciada a partir de uma string UTF8 terminada em zero não gerenciada.
type: docs
weight: 274
url: /pt/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) método

Cria um [String](../../../system/string/) gerenciado a partir de uma string UTF8 terminada em zero não gerenciada.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | IntPtr | Ponteiro para a string não gerenciada. |

### Valor de Retorno

Uma string gerenciada.

## Marshal::PtrToStringAnsi(IntPtr, int) método

Cria um [String](../../../system/string/) gerenciado a partir de uma string UTF8 não gerenciada.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | IntPtr | Ponteiro para a string não gerenciada. |
| length | int | Comprimento da string não gerenciada. |

### Valor de Retorno

Uma string gerenciada.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [Marshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Biblioteca [Aspose.Slides](../../../)