---
title: IterateOver()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Cette fonction property enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable sans méthodes begin(), end() avec un argument de type cible pour (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2432
url: /fr/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) fonction

Cette fonction enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable sans méthodes begin(), end() avec un argument de type cible pour (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type cible, il doit être renvoyé par l'itérateur |
| Enumerable | Le type de l'objet enveloppé |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonction

Cette fonction enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable sans méthodes begin(), end() avec un argument de type cible par défaut pour (auto& value : IterateOver(enumerable)) analogique au code C# suivant foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Enumerable | Le type de l'objet enveloppé |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonction

Cette fonction enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable avec méthodes begin(), end() avec un argument de type cible par défaut pour (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Enumerable | Le type de l'objet enveloppé |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonction

Cette fonction enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable avec méthodes begin(), end() avec un type cible identique au value_type d'origine de l'itérateur.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Enumerable | Le type de l'objet enveloppé |
| T | Le type cible qui doit être renvoyé par l'itérateur |

## System::IterateOver(System::SmartPtr\<Enumerable\>) fonction

Cette fonction enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable avec méthodes begin(), end() avec un type cible différent et le value_type d'origine de l'itérateur.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Enumerable | Le type de l'objet enveloppé |
| T | Le type cible qui doit être renvoyé par l'itérateur |

## System::IterateOver(const Enumerable *) fonction

Cette fonction enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable avec un type cible par défaut.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Enumerable | Le type de l'objet enveloppé |

## System::IterateOver(const Enumerable *) fonction

Cette fonction enveloppe un objet enumerable (ou iterable) afin qu'il puisse être utilisé avec une boucle for à portée. Cette surcharge pour Enumerable sans méthodes begin(), end() avec un argument de type cible pour (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type cible, il doit être renvoyé par l'itérateur |
| Enumerable | Le type de l'objet enveloppé |

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Structure [IsSmartPtr](../issmartptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)