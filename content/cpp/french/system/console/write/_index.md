---
title: Write()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit la représentation sous forme de chaîne de l'objet spécifié vers le flux de sortie standard.
type: docs
weight: 1
url: /fr/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) méthode

Écrit la représentation sous forme de chaîne de l’objet spécifié vers le flux de sortie standard.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l’objet à afficher |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) à afficher |

## Console::Write(bool) méthode

Écrit la représentation sous forme de chaîne de la valeur booléenne vers le flux de sortie standard.

```cpp
static void System::Console::Write(bool value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **bool** | La valeur à afficher |

## Console::Write(char_t) méthode

Écrit la valeur de caractère spécifiée vers le flux de sortie standard.

```cpp
static void System::Console::Write(char_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | char_t | La valeur à afficher |

## Console::Write(const ArrayPtr\<char_t\>\&) méthode

Écrit la représentation sous forme de chaîne du tableau de caractères spécifié vers le flux de sortie standard.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Le tableau à afficher |

## Console::Write(const Decimal\&) méthode

Écrit la représentation sous forme de chaîne de la valeur [Decimal](../../decimal/) vers le flux de sortie standard.

```cpp
static void System::Console::Write(const Decimal &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | La valeur à afficher |

## Console::Write(double) méthode

Écrit la représentation sous forme de chaîne d’une valeur à virgule flottante double précision vers le flux de sortie standard.

```cpp
static void System::Console::Write(double value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | La valeur à afficher |

## Console::Write(float) méthode

Écrit la représentation sous forme de chaîne d’une valeur à virgule flottante simple précision vers le flux de sortie standard.

```cpp
static void System::Console::Write(float value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **float** | La valeur à afficher |

## Console::Write(int32_t) méthode

Écrit la représentation sous forme de chaîne d’une valeur entière 32 bits vers le flux de sortie standard.

```cpp
static void System::Console::Write(int32_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **int32_t** | La valeur à afficher |

## Console::Write(int64_t) méthode

Écrit la représentation sous forme de chaîne d’une valeur entière 64 bits vers le flux de sortie standard.

```cpp
static void System::Console::Write(int64_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **int64_t** | La valeur à afficher |

## Console::Write(const String\&) méthode

Écrit l’objet chaîne spécifié vers le flux de sortie standard.

```cpp
static void System::Console::Write(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | L’objet chaîne à afficher |

## Console::Write(const char_t *) méthode

Écrit la chaîne C spécifiée vers le flux de sortie standard.

```cpp
static void System::Console::Write(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne C à afficher |

## Console::Write(const TypeInfo\&) méthode

Écrit la représentation sous forme de chaîne de la valeur [TypeInfo](../../typeinfo/) vers le flux de sortie standard.

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | La valeur à afficher |

## Console::Write(uint32_t) méthode

Écrit la représentation sous forme de chaîne d’une valeur entière non signée 32 bits vers le flux de sortie standard.

```cpp
static void System::Console::Write(uint32_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | La valeur à afficher |

## Console::Write(uint64_t) méthode

Écrit la représentation sous forme de chaîne d’une valeur entière non signée 64 bits vers le flux de sortie standard.

```cpp
static void System::Console::Write(uint64_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | La valeur à afficher |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) méthode

Écrit la représentation sous forme de chaîne de la plage spécifiée du tableau de caractères spécifié vers le flux de sortie standard.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Le tableau de caractères |
| index | **int32_t** | L'indice dans le tableau où commence la plage à afficher |
| count | **int32_t** | Le nombre d'éléments dans la plage à afficher |

## Console::Write(const String\&, Args\&&…) méthode

Écrit la représentation sous forme de chaîne des arguments spécifiés formatés selon le format spécifié vers le flux de sortie standard.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| The | types des valeurs à afficher |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Le format de chaîne |
| args | Args\&&... | Les valeurs à afficher |

## Console::Write(const char *) méthode



```cpp
static void System::Console::Write(const char *)=delete
```

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)