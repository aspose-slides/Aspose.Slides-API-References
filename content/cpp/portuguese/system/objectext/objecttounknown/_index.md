---
title: ObjectToUnknown()
second_title: Referência da API Aspose.Slides para C++
description: Converte Object para um tipo desconhecido, tratando tanto o tipo de ponteiro inteligente quanto situações de valor encapsulado.
type: docs
weight: 131
url: /pt/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) método

Converte [Object](../../object/) para um tipo desconhecido, tratando tanto o tipo de ponteiro inteligente quanto situações de valor encapsulado.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo para converter [Object](../../object/) para. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) a converter. |

### Valor de retorno

Valor desembrulhado ou ponteiro convertido.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) método

Converte [Object](../../object/) para um tipo desconhecido, tratando tanto o tipo de ponteiro inteligente quanto situações de valor encapsulado.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo para converter [Object](../../object/) para. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) a converter. |

### Valor de retorno

Valor desembrulhado ou ponteiro convertido.

## Veja também

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Estrutura [IsSmartPtr](../../issmartptr/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)