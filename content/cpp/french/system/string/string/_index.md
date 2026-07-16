---
title: String()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur par défaut. Crée un objet string considéré comme nul.
type: docs
weight: 14
url: /fr/system/string/string/
---
## String::String() constructeur

Constructeur par défaut. Crée un objet string considéré comme nul.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructeur

Construit une string à partir d’un littéral de chaîne. Considère le littéral comme une chaîne terminée par un caractère nul et calcule la longueur de la chaîne cible en fonction de la taille du littéral.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) pointeur littéral. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructeur

Construit une string à partir d’un pointeur vers une chaîne de caractères. Considère la chaîne pointée comme terminée par un caractère nul et calcule la longueur de la chaîne cible en fonction du caractère nul.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | Pointeur vers une chaîne de caractères. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructeur

Construit une string à partir d’un littéral de chaîne. Considère le littéral comme une chaîne terminée par un caractère nul en UTF-8 et calcule la longueur de la chaîne cible en fonction de la taille du littéral.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) pointeur littéral. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructeur

Construit une string à partir d’un pointeur vers une chaîne de caractères. Considère la chaîne pointée comme terminée par un caractère nul en UTF-8 et calcule la longueur de la chaîne cible en fonction du caractère nul.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | Pointeur vers une chaîne de caractères. |

## String::String(const char16_t *, int) constructeur

Construit une string à partir d’un pointeur vers une chaîne de caractères et d’une longueur explicite.

```cpp
System::String::String(const char16_t *str, int length)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointeur, peut être un littéral ou un tableau. |
| length | int | Longueur de chaîne explicite |

## String::String(const ReadOnlySpan\<char16_t\>\&) constructeur

Initialise une nouvelle instance de la classe [System.String](../) aux caractères Unicode indiqués dans le span en lecture seule spécifié.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Un span en lecture seule de caractères Unicode. |

## String::String(const char *, int) constructeur

Construit une string à partir d’un pointeur vers une chaîne de caractères et d’une longueur explicite.

```cpp
System::String::String(const char *str, int length)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const char * | [String](../) pointeur vers les données UTF-8, peut être un littéral ou un tableau. |
| length | int | Longueur de chaîne explicite |

## String::String(const char16_t *, int, int) constructeur

Construit une string à partir d’un pointeur vers une chaîne de caractères à partir d’une position de départ en utilisant la longueur.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointeur, peut être un littéral ou un tableau. |
| start | int | Position de départ. |
| length | int | [String](../) longueur. |

## String::String(const char16_t, int) constructeur

Constructeur de remplissage.

```cpp
System::String::String(const char16_t ch, int count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ch | const char16_t | Caractère de remplissage. |
| count | int | Longueur cible. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructeur

Constructeur nullptr. Déclaré comme modèle pour résoudre les priorités avec les autres constructeurs modèles.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Doit être nullptr_t |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructeur

Construit une string à partir d’un littéral de chaîne large. Considère le littéral comme une chaîne terminée par un caractère nul et calcule la longueur de la chaîne cible en fonction de la taille du littéral. La conversion depuis **wchar_t** est longue sur certaines plates-formes, donc aucune conversion implicite n’est autorisée.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) pointeur littéral. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructeur

Construit une string à partir d’un pointeur vers une chaîne de caractères larges. Considère la chaîne pointée comme terminée par un caractère nul et calcule la longueur de la chaîne cible en fonction du caractère nul. La conversion depuis **wchar_t** est longue sur certaines plates-formes, donc aucune conversion implicite n’est autorisée.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | Pointeur vers une chaîne de caractères. |

## String::String(const wchar_t *, int) constructeur

Construit une string à partir d’un pointeur vers une chaîne de caractères larges et d’une longueur explicite. La conversion depuis **wchar_t** est longue sur certaines plates-formes, donc aucune conversion implicite n’est autorisée.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) pointeur, peut être un littéral ou un tableau. |
| length | int | Longueur de chaîne explicite |

## String::String(const wchar_t, int) constructeur

Constructeur de remplissage. La conversion depuis **wchar_t** est longue sur certaines plates-formes, donc aucune conversion implicite n’est autorisée.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ch | const **wchar_t** | Caractère de remplissage. |
| count | int | Longueur cible. |

## String::String(const String\&) constructeur

Constructeur de copie.

```cpp
System::String::String(const String &str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) à copier. |

## String::String(String\&&) constructeur

Constructeur de déplacement.

```cpp
System::String::String(String &&str) noexcept
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) dont les données sont déplacées. |

## String::String(const ArrayPtr\<char16_t\>\&) constructeur

Convertit un tableau complet de caractères en string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) à convertir en string. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructeur

Convertit une sous-plage d’un tableau de caractères en string. Si les paramètres sont hors des limites du tableau, une chaîne vide est construite.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Tableau de caractères. |
| offset | int | Index de début du sous-tableau. |
| len | int | Longueur du sous-tableau. |

## String::String(const codeporting_icu::UnicodeString\&) constructeur

Enveloppe UnicodeString dans [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString à envelopper dans [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) constructeur

Constructeur de déplacement.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString à envelopper dans [String](../). |

## String::String(const std::wstring\&) constructeur

Crée [String](../) à partir d’un widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const std::wstring\& | Widestring à convertir en [String](../). |

## String::String(const std::u16string\&) constructeur

Crée [String](../) à partir d’une chaîne utf16.

```cpp
System::String::String(const std::u16string &str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const std::u16string\& | Chaîne Utf16 à convertir en [String](../). |

## String::String(const std::string\&) constructeur

Crée [String](../) à partir d’une std::string présentée au format UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| utf8str | const std::string\& | std::string à convertir en [String](../). |

## String::String(const std::u32string\&) constructeur

Crée [String](../) à partir d’une std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string à convertir en [String](../). |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)