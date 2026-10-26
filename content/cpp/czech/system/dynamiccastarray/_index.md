---
title: DynamicCastArray()
second_title: Aspose.Slides pro C++ API Reference
description: Provádí přetypování prvků zadaného pole na jiný typ.
type: docs
weight: 2991
url: /cs/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) funkce

Provádí přetypování prvků zadaného pole na jiný typ.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| To | Typ, na který se mají přetypovat prvky zadaného pole |
| From | Typ prvků pole, jehož prvky se mají přetypovat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Sdílený ukazatel na pole obsahující prvky k přetypování |

### Návratová hodnota

Ukazatel na nové pole obsahující prvky typu **To**, ekvivalentní prvkům **from**

Deprecated
:   Přidáno pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* Třída [Array](../array/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)