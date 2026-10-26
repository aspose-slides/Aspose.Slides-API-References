---
title: HoldIfTemporary()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une référence vers une rvalue (const)
type: docs
weight: 14
url: /fr/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) méthode


Renvoie une référence vers une rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) méthode


Renvoie une référence vers une rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) méthode


Copie le lvalue passé dans le holder, puis renvoie la référence du holder.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## Voir aussi

* Structure [HolderInitializer](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)