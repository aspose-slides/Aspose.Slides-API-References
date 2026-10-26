---
title: PrintTo()
second_title: Référence API Aspose.Slides pour C++
description: Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.
type: docs
weight: 2120
url: /fr/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) fonction

Écrit la valeur représentée par l'objet spécifié dans le flux de sortie spécifié.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | L'objet [Decimal](../decimal/) à imprimer dans le flux |
| os | ::std::ostream * | Le flux dans lequel imprimer l'objet spécifié |

## System::PrintTo(const Details_Exception\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) fonction

Imprime la chaîne sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::String](../string/)\& | à imprimer. |
| os | std::ostream * | flux cible. |

## System::PrintTo(TimeSpan, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) fonction

Imprime la valeur sur le flux de sortie. Principalement utilisé pour le débogage.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## See Also

* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Decimal](../decimal/)
* Classe [Details_Exception](../details_exception/)
* Classe [ExceptionWrapper](../exceptionwrapper/)
* Classe [Guid](../guid/)
* Classe [Nullable](../nullable/)
* Classe [Object](../object/)
* Classe [SmartPtr](../smartptr/)
* Classe [String](../string/)
* Classe [TimeSpan](../timespan/)
* Classe [WeakPtr](../weakptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)