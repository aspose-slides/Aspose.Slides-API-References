---
title: GetHashCode()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en hashkod för det angivna skalära värdet.
type: docs
weight: 2484
url: /sv/system/gethashcode/
---
## System::GetHashCode(const T\&) funktion

Returnerar en hashkod för det angivna skalära värdet.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av värdet för vilket funktionen genererar hashkod |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Värdet som hashkoden ska genereras för |

### Returvärde

Hashkoden som genererats för det angivna värdet

## System::GetHashCode(const T\&) funktion

Returnerar en hashkod för det angivna objektet.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objektet för vilket funktionen genererar hashkod |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Den [SmartPtr](../smartptr/) som pekar på objektet för vilket hashkod ska genereras |

### Returvärde

Hashkoden som genererats för det angivna objektet

## System::GetHashCode(const T\&) funktion

Returnerar en hashkod för det angivna objektet som är ett undantag.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objektet för vilket funktionen genererar hashkod |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Exception Wrapper som innehåller objektet för vilket hashkod ska genereras |

### Returvärde

Hashkoden som genererats för det angivna objektet

## System::GetHashCode(const T\&) funktion

Returnerar en hashkod för det angivna objektet som inte är en smart pekare eller ett undantag.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objektet för vilket funktionen genererar hashkod |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | En konstant referens till objektet som hashkoden ska genereras för |

### Returvärde

Hashkoden som genererats för det angivna objektet

## System::GetHashCode(const std::thread::id\&) funktion

Specialisering för std::thread::id; Returnerar hashkoden för det angivna trådobjektet.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Se också

* Struktur [IsSmartPtr](../issmartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)