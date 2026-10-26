---
title: Is()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types boîte (valeur) qui sont exactement cela.
type: docs
weight: 92
url: /fr/system/objectext/is/
---
## ObjectExt::Is(const T\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types boîte (valeur) qui sont exactement cela.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) pour tester l’opérateur 'is'. Ignoré. |

### Valeur de retour

Toujours true

## ObjectExt::Is(const U\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types pointeur optimisée pour les classes 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |
| U | Type testé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const U\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types pointeur.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |
| U | Type testé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const Object\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types valeur.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const Object\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types non convertibles.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

Toujours renvoie false car les types sont non convertibles.

## ObjectExt::Is(const SmartPtr\<U\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types pointeur.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types wrapper d’exception.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const SmartPtr\<Object\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types nullable.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const SmartPtr\<Object\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types boîte avec l’opérateur == défini.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const SmartPtr\<Object\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types boîte sans == défini.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const SmartPtr\<V\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types valeur encapsulés en interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |
| V | Type de l’objet pointé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const SmartPtr\<U\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types enum.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |
| U | Type de l’objet pointé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const WeakPtr\<U\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les types enum vs pointeurs faibles.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |
| U | Type de l’objet pointé. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) pour tester l’opérateur 'is'. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const Nullable\<U\>\&) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour le type [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) type. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(const char16_t *) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les littéraux de chaîne.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) littéral. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## ObjectExt::Is(int32_t) méthode


Implémente la traduction de l’opérateur 'is'. Spécialisation pour les littéraux entiers.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type cible. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **int32_t** | littéral entier. |

### Valeur de retour

True si 'is' renvoie true, false sinon.

## Voir aussi

* Classe [ObjectExt](../)
* Classe [Object](../../object/)
* Classe [SmartPtr](../../smartptr/)
* Classe [ExceptionWrapper](../../exceptionwrapper/)
* Classe [WeakPtr](../../weakptr/)
* Classe [Nullable](../../nullable/)
* Structure [IsBoxable](../../isboxable/)
* Structure [IsSmartPtr](../../issmartptr/)
* Structure [IsExceptionWrapper](../../isexceptionwrapper/)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)