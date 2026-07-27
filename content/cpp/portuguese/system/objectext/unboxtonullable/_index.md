---
title: UnboxToNullable()
second_title: Aspose.Slides para C++ Referência da API
description: Desencapsula o objeto para um tipo anulável.
type: docs
weight: 79
url: /pt/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) método

Desencapsula o objeto para um tipo anulável.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de destino. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempacotar. |
| safe | **bool** | Se true, retorna nullptr em caso de falha; caso contrário, lança InvalidCastException. |

### Valor de Retorno

Valor anulável desempacotado (pode ser nulo).

## Veja Também

* Classe [Nullable](../../nullable/)
* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)