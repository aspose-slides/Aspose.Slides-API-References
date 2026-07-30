---
title: BaseDictionary()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una struttura dati vuota.
type: docs
weight: 14
url: /it/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() costruttore

Crea una struttura dati vuota.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) costruttore

Costruttore di inoltro per passare gli argomenti al costruttore della mappa sottostante.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Args | Tipi degli argomenti da inoltrare alla mappa. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | int | Argomenti da inoltrare al costruttore della mappa sottostante. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) costruttore

Costruttore di copia.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Args | Tipi degli argomenti del costruttore della mappa. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) da cui copiare i dati. |
| args | const Args\&... | Argomenti da inoltrare al costruttore della mappa sottostante. |

## BaseDictionary::BaseDictionary(BaseType *) costruttore

Costruttore di copia.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) da cui copiare i dati. |

## Vedi anche

* Typedef [BaseType](../basetype/)
* Classe [BaseDictionary](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)