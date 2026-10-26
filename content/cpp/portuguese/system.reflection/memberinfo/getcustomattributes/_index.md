---
title: GetCustomAttributes()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um array contendo objetos que representam todos os atributos personalizados aplicados ao tipo representado pelo objeto atual.
type: docs
weight: 66
url: /pt/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const método


Retorna um array contendo objetos que representam todos os atributos personalizados aplicados ao tipo representado pelo objeto atual.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Tipo de atributo a ser procurado. |
| inherit | **bool** | Indica se deve verificar também os atributos herdados. |

## MemberInfo::GetCustomAttributes(bool) const método


Retorna um array contendo objetos que representam todos os atributos personalizados aplicados ao tipo representado pelo objeto atual.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inherit | **bool** | Indica se deve verificar também os atributos herdados. |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)