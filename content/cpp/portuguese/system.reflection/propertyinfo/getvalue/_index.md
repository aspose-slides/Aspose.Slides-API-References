---
title: GetValue()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o valor da propriedade de um objeto específico.
type: docs
weight: 1
url: /pt/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) método

Obtém o valor da propriedade de um objeto específico.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) para ler a propriedade de. |

### Valor de Retorno

Valor da propriedade especificada para o objeto especificado.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) método

Obtém o valor da propriedade de um objeto específico.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) para ler a propriedade de. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Estes são valores de índice opcionais para propriedades indexadas. Para propriedades não indexadas, este valor deve ser nulo. |

### Valor de Retorno

Valor da propriedade especificada para o objeto especificado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)