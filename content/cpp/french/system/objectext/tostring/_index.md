---
title: ToString()
second_title: Référence API Aspose.Slides pour C++
description: Substitution pour la méthode C# ToString afin de fonctionner avec tout type C++.
type: docs
weight: 27
url: /fr/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) littéral à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) objet à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(const T\&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) valeur à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(const T\&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type de pointeur intelligent. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) valeur à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(T\&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type de pointeur intelligent ou [ExceptionWrapper](../../exceptionwrapper/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T\& | Pointeur intelligent ou [ExceptionWrapper](../../exceptionwrapper/) à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(T\&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type scalaire. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T\& | valeur scalaire à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(T\&&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type scalaire. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T\&& | valeur scalaire à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(T\&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type de structure. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T\& | valeur de structure à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(const T\&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type de structure. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | valeur de structure à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## ObjectExt::ToString(T\&&) méthode

Substitution de la méthode C# ToString pour fonctionner avec tout type C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type scalaire. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T\&& | valeur scalaire à convertir en chaîne. |

### Valeur de retour

[String](../../string/) représentation de **obj**.

## Voir aussi

* Classe [String](../../string/)
* Classe [ObjectExt](../)
* Classe [Nullable](../../nullable/)
* Structure [IsSmartPtr](../../issmartptr/)
* Structure [IsExceptionWrapper](../../isexceptionwrapper/)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)