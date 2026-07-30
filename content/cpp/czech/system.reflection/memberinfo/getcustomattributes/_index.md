---
title: GetCustomAttributes()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací pole obsahující objekty, které představují všechny vlastní atributy aplikované na typ reprezentovaný aktuálním objektem.
type: docs
weight: 66
url: /cs/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const metoda

Vrátí pole obsahující objekty, které představují všechny vlastní atributy použité na typu reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Typ atributu, který se hledá. |
| inherit | **bool** | Zda také zkontrolovat zděděné atributy. |

## MemberInfo::GetCustomAttributes(bool) const metoda

Vrátí pole obsahující objekty, které představují všechny vlastní atributy použité na typu reprezentovaném aktuálním objektem.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inherit | **bool** | Zda také zkontrolovat zděděné atributy. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [MemberInfo](../)
* Jmenný prostor [System::Reflection](../../)
* Knihovna [Aspose.Slides](../../../)