---
title: ToString()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.
type: docs
weight: 27
url: /it/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) letterale da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Nullable](../../nullable/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) oggetto da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(const T\&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) valore da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(const T\&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di smart pointer. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) valore da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(T\&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo smart pointer o [ExceptionWrapper](../../exceptionwrapper/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T\& | Smart pointer o [ExceptionWrapper](../../exceptionwrapper/) da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(T\&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo scalare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T\& | Valore scalare da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(T\&&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo scalare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T\&& | Valore scalare da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(T\&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo struttura. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T\& | Valore di struttura da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(const T\&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo struttura. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Valore di struttura da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## ObjectExt::ToString(T\&&) metodo

Sostituzione del metodo ToString di C# per funzionare su qualsiasi tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo scalare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T\&& | Valore scalare da convertire in stringa. |

### Valore di ritorno

[String](../../string/) rappresentazione di **obj**.

## Vedi anche

* Classe [String](../../string/)
* Classe [ObjectExt](../)
* Classe [Nullable](../../nullable/)
* Struttura [IsSmartPtr](../../issmartptr/)
* Struttura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)