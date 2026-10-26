---
title: UnknownToObject()
second_title: Aspose.Slides para C++ Referência da API
description: Converte tipo desconhecido para Object, lidando com situações de tipo ponteiro inteligente e tipo de valor.
type: docs
weight: 118
url: /pt/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) método

Converte tipo desconhecido para [Object](../../object/), lidando com situações de tipo ponteiro inteligente e tipo de valor.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo a ser convertido para [Object](../../object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T | [Object](../../object/) para converter. |

### Valor de retorno

Ponteiro inteligente para [Object](../../object/) sendo o ponteiro convertido ou valor encapsulado.

## ObjectExt::UnknownToObject(const T\&) método

Converte tipo desconhecido para [Object](../../object/), lidando com situações de tipo ponteiro inteligente e tipo de valor.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo a ser convertido para [Object](../../object/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para converter. |

### Valor de retorno

Ponteiro inteligente para [Object](../../object/) sendo o ponteiro convertido ou valor encapsulado.

## Veja Também

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Estrutura [IsSmartPtr](../../issmartptr/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)