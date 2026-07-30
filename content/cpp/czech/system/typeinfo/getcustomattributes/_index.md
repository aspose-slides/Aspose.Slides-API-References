---
title: GetCustomAttributes()
second_title: Aspose.Slides pro C++ API Reference
description: Vrátí pole obsahující objekty, které představují všechny vlastní atributy aplikované na typ.
type: docs
weight: 586
url: /cs/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const metoda

Vrátí pole obsahující objekty, které představují všechny vlastní atributy aplikované na typ.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const metoda

Vrátí pole obsahující objekty, které představují konkrétní atributy aplikované na typ.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Typ atributu, který se má hledat. |
| inherit | **bool** | Zda hledat také zděděné atributy. |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)