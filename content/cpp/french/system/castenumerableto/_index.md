---
title: CastEnumerableTo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue le transtypage explicite des éléments de l'objet énumérable spécifié vers un type différent.
type: docs
weight: 2926
url: /fr/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) fonction

Effectue le transtypage explicite des éléments de l'objet énumérable spécifié vers un type différent.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| To | Le type vers lequel les éléments de l'objet énumérable seront convertis statiquement |
| From | Le type de l'objet énumérable |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| enumerable | const From\& | Objet énumérable contenant les éléments à convertir |

### Valeur de retour

Un pointeur vers une nouvelle collection contenant des éléments de type **To** équivalents aux éléments de **enumerable**.

## System::CastEnumerableTo(const From\&) fonction

Effectue le transtypage explicite des éléments de l'objet énumérable spécifié vers un type différent.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| To | Le type vers lequel les éléments de l'objet énumérable seront convertis statiquement |
| From | Le type de l'objet énumérable |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| enumerable | const From\& | est un héritier de l'objet Enumerable avec une méthode get_Count définie et contenant les éléments à convertir |

### Valeur de retour

Un pointeur vers une nouvelle collection contenant des éléments de type **To** équivalents aux éléments de **enumerable**.

## Voir aussi

* Classe [ListPtr](../../system.collections.generic/listptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)