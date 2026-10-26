---
title: Format()
second_title: Référence de l'API Aspose.Slides pour C++
description: Formate la chaîne au style C#.
type: docs
weight: 885
url: /fr/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) méthode


Formate la chaîne au style C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Args | Arguments pour formater la chaîne. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format à utiliser pour convertir les arguments en chaînes. |
| format | const [String](../)\& | Chaîne de format. |
| args | const Args\&... | Arguments pour formater la chaîne. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) méthode


Formate la chaîne au style C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Args | Arguments pour formater la chaîne. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | std::nullptr_t | Chaîne de format. |
| args | const [String](../)\& | Arguments pour formater la chaîne. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) méthode


Formate la chaîne au style C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Args | Arguments pour formater la chaîne. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | std::nullptr_t | Chaîne de format. |
| args | const char16_t(&) | Arguments pour formater la chaîne. |

## String::Format(const String\&, const Args\&...) méthode


Formate la chaîne au style C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Args | Arguments pour formater la chaîne. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../)\& | Chaîne de format. |
| args | const Args\&... | Arguments pour formater la chaîne. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) méthode


Formate la chaîne au style C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Arguments pour formater la chaîne. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../)\& | Chaîne de format. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Arguments pour formater la chaîne. |

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)