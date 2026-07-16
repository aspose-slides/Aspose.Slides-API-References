---
title: Insert()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère une chaîne dans la position fixe du constructeur.
type: docs
weight: 183
url: /fr/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) méthode


Insère une chaîne dans la position fixe du constructeur.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Position où insérer les caractères. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) à insérer. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Insert(int32_t, const String\&, int32_t) méthode


Insère une chaîne répétée dans la position fixe du constructeur.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position où insérer les caractères. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) à insérer. |
| count | **int32_t** | Combien de fois répéter la chaîne **value**. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Insert(int, char_t) méthode


Insère un caractère dans la position fixe du constructeur.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Position où insérer les caractères. |
| ch | char_t | Caractère à insérer. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) méthode


Insère des caractères dans la position fixe du constructeur.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer les caractères. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) à partir duquel insérer la tranche. |
| startIndex | int | [Array](../../../system/array/) indice de début de la tranche. |
| charCount | int | [Array](../../../system/array/) longueur de la tranche. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Insert(int, T) méthode


Insère une valeur dans la position fixe du constructeur.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Parameter | type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Position où insérer les caractères. |
| value | T | Valeur à formater et insérer. |

### Valeur de retour

Ce pointeur.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)