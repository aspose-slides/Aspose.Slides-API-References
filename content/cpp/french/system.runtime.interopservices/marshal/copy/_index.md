---
title: Copy()
second_title: Référence API Aspose.Slides pour C++
description: Implémente la sémantique public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /fr/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) méthode

Implémente la sémantique public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| container | Destination container type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| source | const IntPtr | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const void *, container\&&, int, int) méthode

Implémente la sémantique public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| container | Destination container type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| source | const void * | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, void *, int) méthode

Implémente la sémantique public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| container | Source container type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | void * | Destination data pointer. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, IntPtr, int) méthode

Implémente la sémantique public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| container | Source container type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | IntPtr | Destination data pointer. |
| length | int | Number of elements to copy. |

## Voir aussi

* Classe [Marshal](../)
* Espace de noms [System::Runtime::InteropServices](../../)
* Bibliothèque [Aspose.Slides](../../../)