---
title: Concat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Concatène un tableau de chaînes.
type: docs
weight: 1
url: /fr/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) function

Concatène un tableau de chaînes.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) de chaînes à joindre. |

### Valeur retournée

Chaîne concaténée.

## System::StringExtra::Concat(const String\&, const String\&) function

Concatène des chaînes.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Première chaîne à concaténer. |
| str1 | const [String](../../system/string/)\& | Deuxième chaîne à concaténer. |

### Valeur retournée

Chaînes de paramètres concaténées.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) function

Concatène des chaînes.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Première chaîne à concaténer. |
| str1 | const [String](../../system/string/)\& | Deuxième chaîne à concaténer. |
| str2 | const [String](../../system/string/)\& | Troisième chaîne à concaténer. |

### Valeur retournée

Chaînes de paramètres concaténées.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) function

Concatène des chaînes.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Première chaîne à concaténer. |
| str1 | const [String](../../system/string/)\& | Deuxième chaîne à concaténer. |
| str2 | const [String](../../system/string/)\& | Troisième chaîne à concaténer. |
| str3 | const [String](../../system/string/)\& | Quatrième chaîne à concaténer. |

### Valeur retournée

Chaînes de paramètres concaténées.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

Convertit plusieurs objets en chaîne et concatène les chaînes résultantes. Spécialisation pour les types [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) à convertir et à joindre. |

### Valeur retournée

[String](../../system/string/) valeur concaténée à partir des représentations en chaîne de tous les objets passés.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

Convertit plusieurs objets en chaîne et concatène les chaînes résultantes. Spécialisation pour les types arithmétiques.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) à convertir et à joindre. |

### Valeur retournée

[String](../../system/string/) valeur concaténée à partir des représentations en chaîne de tous les objets passés.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

Convertit plusieurs objets en chaîne et concatène les chaînes résultantes. Spécialisation pour les structures et autres types valeur.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) à convertir et à joindre. |

### Valeur retournée

[String](../../system/string/) valeur concaténée à partir des représentations en chaîne de tous les objets passés.

## Voir aussi

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)