---
title: SetValue()
second_title: Referência da API Aspose.Slides para C++
description: Define o valor da propriedade para um objeto específico.
type: docs
weight: 14
url: /pt/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) método

Define o valor da propriedade para um objeto específico.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) para gravar a propriedade. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Valor da propriedade a ser definido. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) método

Define o valor da propriedade para um objeto específico.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) para gravar a propriedade. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Esses são valores de índice opcionais para propriedades indexadas. Para propriedades não indexadas, este valor deve ser nulo. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Valor da propriedade a ser definido. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)