---
title: Parse()
second_title: Aspose.Slides pro C++ API Reference
description: "Zabaluje hodnotu konstanty výčtu určeného výčtem se zadaným názvem. Parametr určuje, zda se má při interpretaci řetězce udávajícího název konstanty výčtu ignorovat velikost písmen."
type: docs
weight: 53
url: /cs/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) metoda

Zabalí hodnotu konstanty výčtu určeného výčtem se zadaným názvem. Parametr určuje, zda se má při interpretaci řetězce, který udává název konstanty výčtu, ignorovat velikost písmen.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Určuje typ výčtu |
| str | const [String](../../string/)\& | Název konstanty výčtu, jejíž hodnota má být zabalena |
| ignoreCase | **bool** | Určuje, zda se má při interpretaci řetězce představujícího název konstanty výčtu ignorovat velikost písmen |

### Návratová hodnota

Sdílený ukazatel na objekt představující zabalenou hodnotu určené konstanty výčtu

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) metoda

Zabalí hodnotu konstanty výčtu určeného výčtem se zadaným názvem.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Určuje typ výčtu |
| str | const [String](../../string/)\& | Název konstanty výčtu, jejíž hodnota má být zabalena |

### Návratová hodnota

Sdílený ukazatel na objekt představující zabalenou hodnotu určené konstanty výčtu

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* třída [Object](../../object/)
* třída [TypeInfo](../../typeinfo/)
* třída [String](../../string/)
* třída [BoxedValueBase](../)
* jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)