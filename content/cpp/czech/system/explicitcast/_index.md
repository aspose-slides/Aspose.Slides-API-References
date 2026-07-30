---
title: ExplicitCast()
second_title: Aspose.Slides pro C++ – příručka API
description: Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se, když jsou zdrojový a výsledný typ stejné.
type: docs
weight: 2627
url: /cs/system/explicitcast/
---
## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se, když jsou zdrojový a výsledný typ stejný.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se, když je potřeba jednoduché přetypování podobné konstruktoru.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro obalování výjimek.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro přetypování objektu na výjimku.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se, když jsou zdroj i výsledek chytré ukazatele (bez explicitního SmartPtr<...> ve výsledném typu).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(Source) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se při přetypování surového ukazatele na chytrý ukazatel.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | Source | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se, když jsou zdroj i výsledek chytré ukazatele (s explicitním SmartPtr<...> ve výsledném typu).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro rozbalení objektu na nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro zabalení nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro rozbalení nullable objektu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro zabalení výčtu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro kopírování hodnotových typů na haldu, když by měl být hodnotový typ odkazován jako chytrý ukazatel (v generických typech omezených na rozhraní, ale specializovaných na strukturu implementující toto rozhraní).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro získání rozhraní z hodnotových typů.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro obecné zabalení.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro [System::String](../string/) zabalení.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro rozbalení rozhraní.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro obecné rozbalení.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro přetypování nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## System::ExplicitCast(const Source\&) function

Převádí zdrojový typ na výsledek pomocí explicitního přetypování. Používá se pro přetypování mezi poli.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Source | Zdrojový typ. |
| Result | Výsledný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) k přetypování. |

### Návratová hodnota

Výsledek přetypování.

## Viz také

* Typedef [Exception](../exception/)
* Třída [SmartPtr](../smartptr/)
* Třída [BoxedValueBase](../boxedvaluebase/)
* Struktura [CastResult](../castresult/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)