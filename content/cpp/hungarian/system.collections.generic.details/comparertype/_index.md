---
title: ComparerType
second_title: Aspose.Slides C++ API-referencia
description: Az elemeket a 'less' szemantika szerint hasonlítja össze.
type: docs
weight: 144
url: /hu/system.collections.generic.details/comparertype/
---
## ComparerType struktúra

Az elemeket a 'less' szemantika szerint hasonlítja össze.

```cpp
template<typename T>class ComparerType
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az összehasonlított elemek típusa. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [IComparable](../../system/icomparable/) interfészt megvalósító értéktípusokat hasonlítja össze. |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Primitív értéktípusokat és a [IComparable](../../system/icomparable/) interfészt nem megvalósító objektumokat hasonlítja össze. |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Lebegőpontos típusokat hasonlítja össze. |

## Lásd még

* Névtere [System::Collections::Generic::Details](../)
* Könyvtár [Aspose.Slides](../../)