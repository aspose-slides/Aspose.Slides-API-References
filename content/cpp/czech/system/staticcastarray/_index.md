---
title: StaticCastArray()
second_title: Aspose.Slides pro C++ API Reference
description: Provádí přetypování prvků zadaného pole na jiný typ. Přepis pro případy, kdy je From objekt typu SmartPtr.
type: docs
weight: 2978
url: /cs/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funkce


Provádí přetypování prvků zadaného pole na jiný typ. Přepis pro případy, kdy je From [SmartPtr](../smartptr/) objekt.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parametry šablony

| Parameter | Popis |
| --- | --- |
| To | Typ, na který se mají přetypovat prvky zadaného pole |
| From | Typ prvků pole, které se mají přetypovat |

### Argumenty

| Parameter | Typ | Popis |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Sdílený ukazatel na pole obsahující prvky k přetypování |

### Návratová hodnota

Ukazatel na nové pole obsahující prvky typu **To** ekvivalentní prvkům **from**

Zastaralé
:   Přidáno pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funkce


Provádí přetypování prvků zadaného pole na jiný typ. Přepis pro případy, kdy je From typ Boxable a To je [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parametry šablony

| Parameter | Popis |
| --- | --- |
| To | Typ, na který se mají přetypovat prvky zadaného pole |
| From | Typ prvků pole, které se mají přetypovat |

### Argumenty

| Parameter | Typ | Popis |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Sdílený ukazatel na pole obsahující prvky k přetypování |

### Návratová hodnota

Ukazatel na nové pole obsahující prvky typu **To** ekvivalentní prvkům **from**

Zastaralé
:   Přidáno pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* Třída [Array](../array/)
* Třída [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Jmenný prostor [System](../)
* Library [Aspose.Slides](../../)