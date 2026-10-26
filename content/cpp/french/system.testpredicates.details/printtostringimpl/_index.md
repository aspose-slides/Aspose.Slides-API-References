---
title: PrintToStringImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Imprime la sous-classe System::Object en chaîne en utilisant la méthode ToString()."
type: docs
weight: 14
url: /fr/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) fonction


Imprime la sous-classe [System::Object](../../system/object/) en chaîne en utilisant la méthode ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type de classe final. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Pointeur vers l'objet à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

[String](../../system/string/) représentation de l'objet passé ou "nullptr", si **value** est nul.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) fonction


Imprime la sous-classe [System::Object](../../system/object/) en chaîne en utilisant la méthode ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type de classe final. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Pointeur vers l'objet à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

[String](../../system/string/) représentation de l'objet passé ou "nullptr", si **value** est nul.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonction


Imprime l'objet en chaîne en utilisant la méthode ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

[String](../../system/string/) représentation de l'objet passé.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonction


Imprime l'objet en chaîne en utilisant la méthode PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

[String](../../system/string/) représentation de l'objet passé.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonction


Imprime l'objet en chaîne en utilisant la méthode PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

[String](../../system/string/) représentation de l'objet passé.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) fonction


Imprime la paire en chaîne.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Premier argument de type de la paire. |
| T2 | Deuxième argument de type de la paire. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

Représentations sous forme de chaîne des composants premier et second de la paire.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) fonction


Imprime la paire en chaîne.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Premier argument de type de la paire. |
| T2 | Deuxième argument de type de la paire. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

Représentations sous forme de chaîne des composants premier et second de la paire.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonction


Imprime les conteneurs de style STL en chaîne en imprimant leurs éléments (pas plus de 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) à imprimer. |
| s | long long | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

Représentations sous forme de chaîne des éléments contenus.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) fonction


Imprime d'autres types en chaîne en utilisant les fonctions fournies par gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type [Object](../../system/object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) à imprimer. |
| s | int | Paramètre de service servant de sélecteur de surcharge de fonction en fonction du type de ce paramètre ; la valeur du paramètre est ignorée |

### Valeur de retour

[String](../../system/string/) représentations de l'objet passé.

## Voir aussi

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [WeakPtr](../../system/weakptr/)
* Classe [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Classe [Object](../../system/object/)
* Structure [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Structure [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Structure [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Espace de noms [System::TestPredicates::Details](../)
* Bibliothèque [Aspose.Slides](../../)