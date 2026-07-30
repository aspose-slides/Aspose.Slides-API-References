---
title: AsCast()
second_title: Aspose.Slides pro C++ API Reference
description: Přetypovává zdrojový typ na výsledný typ pomocí přetypování operátorem 'as'. Používá se, když je potřeba jednoduché přetypování podobné konstruktoru.
type: docs
weight: 2640
url: /cs/system/ascast/
---
## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se, když je potřeba jednoduché přetypování podobné konstruktoru.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
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

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se, když jsou zdrojový a výsledný typ stejný.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
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

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro obalování výjimek.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
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

Výsledek přetypování. Vrací nullptr, pokud není dostupná žádná konverze.

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro přetypování objektu na výjimku.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
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

Výsledek přetypování. Vrací nullptr, pokud není dostupná žádná konverze.

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se, když jsou zdroj a výsledek oba chytré ukazatele.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

Výsledek přetypování. Vrací nullptr, pokud není dostupná žádná konverze.

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se, když jsou zdroj a výsledek oba chytré ukazatele (s explicitním SmartPtr<...> ve výsledném typu).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
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

Výsledek přetypování. Vrací nullptr, pokud není dostupná žádná konverze.

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro rozbalení objektu na nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
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

Výsledek přetypování. Vrací prázdný nullable, pokud není dostupná žádná konverze.

## System::AsCast(const Source\&) function


Neplatné rozbalení na typ, který není objektem.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
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

Vždy vrací null.

## System::AsCast(const Source\&) function


Neplatné rozbalení na typ, který není objektem.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
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

Vždy vrací null.

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro balení nullable objektu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
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

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro balení běžného objektu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro balení běžného objektu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro rozbalení řetězce.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
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

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro případování nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

## System::AsCast(const Source\&) function


Přetypovává zdrojový typ na výsledek pomocí přetypování operátorem 'as'. Používá se pro přetypování mezi poli.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
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

Výsledek přetypování. Vrací nullptr, pokud není dostupná žádná konverze pro kterýkoli prvek pole.

## Viz také

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)