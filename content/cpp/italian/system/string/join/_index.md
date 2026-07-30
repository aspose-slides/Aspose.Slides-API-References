---
title: Join()
second_title: Riferimento API di Aspose.Slides per C++
description: Unisce l'array usando la stringa come separatore.
type: docs
weight: 846
url: /it/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) metodo

Unisce l'array usando la stringa come separatore.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) da inserire tra gli elementi dell'array durante l'unione. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) di parti da unire. |
| startIndex | int | Primo indice nell'array da cui iniziare l'unione. |
| count | int | Numero di elementi dell'array da unire. -1 significa 'fino alla fine dell'array'. |

### Valore di ritorno

[String](../) che rappresenta gli elementi dell'array uniti.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) metodo

Unisce l'array usando la stringa come separatore.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) da inserire tra gli elementi dell'array durante l'unione. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView di parti da unire. |
| startIndex | int | Primo indice nell'array da cui iniziare l'unione. |
| count | int | Numero di elementi dell'array da unire. -1 significa 'fino alla fine dell'array'. |

### Valore di ritorno

[String](../) che rappresenta gli elementi dell'array uniti.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) metodo

Unisce l'array usando la stringa come separatore.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) da inserire tra gli elementi dell'array durante l'unione. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - oggetto enumerabile di parti |

### Valore di ritorno

[String](../) che rappresenta gli elementi uniti.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) metodo

Unisce l'array usando la stringa come separatore.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) da inserire tra gli elementi dell'array durante l'unione. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) di parti da unire. |

### Valore di ritorno

[String](../) che rappresenta gli elementi uniti.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [Object](../../object/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)