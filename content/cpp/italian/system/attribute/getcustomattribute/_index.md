---
title: GetCustomAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un attributo personalizzato di un tipo specificato applicato a un tipo specificato.
type: docs
weight: 1
url: /it/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) metodo

Restituisce un attributo personalizzato di un tipo specificato applicato a un tipo specificato.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Tipo dell'attributo di cui viene recuperato |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Tipo dell'attributo da recuperare |

### Valore di ritorno

Un attributo recuperato o null se il tipo specificato non ha un attributo del tipo specificato.

## Vedi anche

* Typedef [ptr](../../object/ptr/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [Attribute](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)