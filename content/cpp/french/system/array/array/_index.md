---
title: Array()
second_title: Référence API Aspose.Slides pour C++
description: Construit un tableau vide.
type: docs
weight: 1
url: /fr/system/array/array/
---
## Array::Array() constructeur

Construit un tableau vide.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) constructeur

Constructeur de remplissage.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| count | int | Taille initiale du tableau |
| init | const T\& | Valeur initiale utilisée pour remplir le tableau avec |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructeur

Constructeur de remplissage.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ValueType | Type de la valeur initiale |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Taille initiale du tableau |
| init | [ValueType](../valuetype/) | Valeur initiale utilisée pour remplir le tableau avec |

## Array::Array(int, const T) constructeur

Constructeur de remplissage.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| count | int | Taille initiale du tableau |
| inits | const T | Valeurs pour remplir le tableau avec |

## Array::Array(vector_t\&&) constructeur

Constructeur de déplacement.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, dont les éléments sont acquis par le tableau |

## Array::Array(const vector_t\&) constructeur

Constructeur de copie.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector dont les valeurs sont copiées |

## Array::Array(const std::vector\<Q\>\&) constructeur

Construit un objet [Array](../) et le remplit avec des valeurs copiées d'un objet std::vector dont le type des valeurs est le même que **T** mais différent de **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Le type des éléments de l'objet std::vector dont on copie les éléments |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector dont on copie les valeurs |

## Array::Array(std::vector\<Q\>\&&) constructeur

Construit un objet [Array](../) et le remplit avec des valeurs déplacées d'un objet std::vector dont le type des valeurs est le même que **T** mais différent de **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Le type des éléments de l'objet std::vector dont on déplace les éléments |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector dont on copie les valeurs |

## Array::Array(std::initializer_list\<UnderlyingType\>) constructeur

Construit un objet [Array](../) et le remplit avec des valeurs provenant de la liste d'initialisation spécifiée contenant des éléments de type **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Liste d'initialisation contenant les éléments pour remplir le tableau avec |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructeur

Construit un objet [Array](../) et le remplit avec des valeurs provenant du tableau spécifié contenant des éléments de type **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| InitArraySize | Nombre d'éléments du tableau **init**. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) à copier dans le tableau en cours de construction. |

## Array::Array(std::initializer_list\<bool\>, int) constructeur

Construit un objet [Array](../) et le remplit avec des valeurs provenant de la liste d'initialisation spécifiée contenant des éléments de type bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Liste d'initialisation contenant les éléments pour remplir le tableau avec |

## Voir aussi

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)