---
title: Join()
second_title: Référence de l'API Aspose.Slides pour C++
description: Concatène un tableau en utilisant la chaîne comme séparateur.
type: docs
weight: 846
url: /fr/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method

Joint le tableau en utilisant la chaîne comme séparateur.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) à placer entre les éléments du tableau lors de la concaténation. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) des parties à joindre. |
| startIndex | int | Premier indice du tableau à partir duquel commencer la concaténation. |
| count | int | Nombre d'éléments du tableau à concaténiser. -1 signifie « jusqu'à la fin du tableau ». |

### Valeur de retour

[String](../) représentant les éléments du tableau concaténés.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method

Joint le tableau en utilisant la chaîne comme séparateur.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) à placer entre les éléments du tableau lors de la concaténation. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView des parties à joindre. |
| startIndex | int | Premier indice du tableau à partir duquel commencer la concaténation. |
| count | int | Nombre d'éléments du tableau à concaténiser. -1 signifie « jusqu'à la fin du tableau ». |

### Valeur de retour

[String](../) représentant les éléments du tableau concaténés.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method

Joint le tableau en utilisant la chaîne comme séparateur.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) à placer entre les éléments du tableau lors de la concaténation. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - objet énumérable de parties |

### Valeur de retour

[String](../) représentant les éléments concaténés.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method

Joint le tableau en utilisant la chaîne comme séparateur.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) à placer entre les éléments du tableau lors de la concaténation. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) des parties à joindre. |

### Valeur de retour

[String](../) représentant les éléments concaténés.

## Voir également

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [Object](../../object/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)