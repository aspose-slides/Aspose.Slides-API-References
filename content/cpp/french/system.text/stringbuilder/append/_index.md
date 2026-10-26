---
title: Append()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un caractère au StringBuilder.
type: docs
weight: 118
url: /fr/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) méthode

Ajoute un caractère au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| c | char_t | Valeur du caractère. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(char_t, int) méthode

Ajoute des caractères au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| c | char_t | Valeur du caractère. |
| count | int | Nombre de fois où répéter le caractère inséré. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) méthode

Ajoute un tableau de caractères au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caractères à ajouter. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) méthode

Ajoute une tranche de tableau de caractères au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caractères à ajouter. |
| startIndex | int | Indice de début de la tranche. |
| charCount | int | Longueur de la tranche. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(const String\&) méthode

Ajoute une chaîne au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) à ajouter. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(const String\&, int, int) méthode

Ajoute une tranche de chaîne au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) à ajouter. |
| startIndex | int | Indice de début de la tranche. |
| charCount | int | Longueur de la tranche. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(const SharedPtr\<T\>\&) méthode

Ajoute la représentation sous forme de chaîne de l'objet au StringBuilder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../../system/object/) type. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) à sérialiser et à ajouter. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) méthode

Ajoute le contenu du StringBuilder au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | StringBuilder dont le contenu doit être ajouté. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(float) méthode

Ajoute une valeur en virgule flottante au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| f | **float** | Valeur à sérialiser et à ajouter. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(double) méthode

Ajoute une valeur en virgule flottante au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| df | **double** | Valeur à sérialiser et à ajouter. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(int) méthode

Ajoute une valeur entière au StringBuilder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| i | int | Valeur à sérialiser et à ajouter. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(T) méthode

Ajoute une valeur arithmétique au StringBuilder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type arithmétique. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T | Valeur à sérialiser et à ajouter. |

### Valeur de retour

Ce pointeur.

## StringBuilder::Append(E) méthode

Ajoute la représentation sous forme de chaîne de la valeur d'énumération au StringBuilder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| E | [Enum](../../../system/enum/) type. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| e | E | Valeur à sérialiser et à ajouter. |

### Valeur de retour

Ce pointeur.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)