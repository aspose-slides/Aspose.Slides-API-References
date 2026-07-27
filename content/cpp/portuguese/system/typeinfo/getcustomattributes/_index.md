---
title: GetCustomAttributes()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um array contendo objetos que representam todos os atributos personalizados aplicados ao tipo.
type: docs
weight: 586
url: /pt/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const method


Retorna um array contendo objetos que representam todos os atributos personalizados aplicados ao tipo.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const method


Retorna um array contendo objetos que representam atributos específicos aplicados ao tipo.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Tipo do atributo a ser encontrado. |
| inherit | **bool** | Indica se também deve procurar atributos herdados. |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [SmartPtr](../../smartptr/)
* Classe [TypeInfo](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)