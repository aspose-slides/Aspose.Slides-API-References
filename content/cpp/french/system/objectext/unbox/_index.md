---
title: Unbox()
second_title: Référence API Aspose.Slides pour C++
description: Déballe les types valeur après conversion en Object. Implémentation pour les types enum.
type: docs
weight: 53
url: /fr/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) méthode


Déballage des types valeur après conversion en [Object](../../object/). Implémentation pour les types énumération.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type [Enum](../../enum/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) à déballer. |

### Valeur de retour

[Enum](../../enum/) valeur.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) méthode


Déballage des types valeur après conversion en [Object](../../object/). Implémentation pour les types non-enum et non-nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) à déballer. |

### Valeur de retour

Valeur déballée.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) méthode


Déballage des types valeur après conversion en [Object](../../object/). Implémentation pour les types non-enum et non-nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) à déballer. |

### Valeur de retour

Valeur déballée.

## ObjectExt::Unbox(E) méthode


Déballage des types enum en entier.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type entier de destination. |
| E | Type enum source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| e | E | Valeur à déballer. |

### Valeur de retour

Représentation entière de l'énumération.

## ObjectExt::Unbox(E) méthode


Convertit les types enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type enum de destination. |
| E | Type enum source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| e | E | Valeur à déballer. |

### Valeur de retour

Valeur d'énumération convertie.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) méthode


Déballage des valeurs de chaîne.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) à déballer |

### Valeur de retour

[String](../../string/) représentation de la chaîne emballée, peut être nulle si la chaîne emballée était nulle.

## Voir aussi

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)