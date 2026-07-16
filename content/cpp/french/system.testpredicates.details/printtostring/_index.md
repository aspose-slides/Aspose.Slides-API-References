---
title: PrintToString()
second_title: Référence de l'API Aspose.Slides for C++
description: Convertit l'objet en chaîne en sélectionnant la fonction de sérialisation appropriée.
type: docs
weight: 1
url: /fr/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) fonction

Convertit l'objet en chaîne en sélectionnant la fonction de sérialisation appropriée.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) à imprimer. |

### Valeur de retour

[String](../../system/string/) représentations de l'objet passé.

## System::TestPredicates::Details::PrintToString(const T\&) fonction

Imprime les conteneurs de type ICollection en chaîne en affichant leurs éléments (pas plus de 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) à imprimer. |

### Valeur de retour

Représentations de chaîne jointes des éléments contenus.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) fonction

Imprime nullptr en chaîne.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Valeur de retour

"nullptr" string.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) fonction

Imprime les collections [IEnumerable<bool>](../../system.collections.generic/ienumerable/) en chaîne en affichant leurs éléments (pas plus de 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) à imprimer. |

### Valeur de retour

Représentations de chaîne jointes des éléments contenus.

## Voir aussi

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Structure [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Espace de noms [System::TestPredicates::Details](../)
* Bibliothèque [Aspose.Slides](../../)