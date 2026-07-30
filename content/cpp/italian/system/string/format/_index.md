---
title: Format()
second_title: Riferimento API di Aspose.Slides per C++
description: Formatta la stringa in stile C#.
type: docs
weight: 885
url: /it/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) metodo

Formatta la stringa in stile C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Args | Argomenti per formattare la stringa. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato da utilizzare per convertire gli argomenti in stringhe. |
| format | const [String](../)\& | Stringa di formato. |
| args | const Args\&... | Argomenti per formattare la stringa. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) metodo

Formatta la stringa in stile C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Args | Argomenti per formattare la stringa. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | std::nullptr_t | Stringa di formato. |
| args | const [String](../)\& | Argomenti per formattare la stringa. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) metodo

Formatta la stringa in stile C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Args | Argomenti per formattare la stringa. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | std::nullptr_t | Stringa di formato. |
| args | const char16_t(&) | Argomenti per formattare la stringa. |

## String::Format(const String\&, const Args\&...) metodo

Formatta la stringa in stile C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Args | Argomenti per formattare la stringa. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../)\& | Stringa di formato. |
| args | const Args\&... | Argomenti per formattare la stringa. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) metodo

Formatta la stringa in stile C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Argomenti per formattare la stringa. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../)\& | Stringa di formato. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argomenti per formattare la stringa. |

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)