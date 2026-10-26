---
title: Delegate()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur par défaut. Construit l'objet delegate qui ne pointe sur rien.
type: docs
weight: 1
url: /fr/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() méthode

Constructeur par défaut. Construit l'objet delegate qui ne pointe sur rien.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) méthode




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) méthode

Constructeur de copie par déplacement. Prend la possession d'une entité pointée par le delegate spécifié.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| o | Delegate\&& | L'objet Delegate dont l'entité pointée est déplacée |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) méthode

Constructeur. Construit un objet delegate à partir du pointeur spécifié vers une fonction libre ou une méthode statique.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Le | type du pointeur de fonction ou de méthode statique accepté par le constructeur comme argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| function | T | Pointeur vers une fonction ou une méthode statique qui sera pointée par la nouvelle instance Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) méthode

Constructeur. Construit un delegate à partir du pointeur spécifié vers l'objet fonction généré par std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Le | type de l'objet fonction généré par std::bind() accepté par le constructeur comme argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| function | T | Pointeur vers une "bind expression" - un pointeur de fonction généré par std::bind() - qui sera pointé par la nouvelle instance Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) méthode

Constructeur. Construit un delegate à partir de l'objet fonction spécifié.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet fonction accepté par le constructeur comme argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functor_tag | int | Une valeur entière factice ; cet argument est utilisé pour résoudre l'ambiguïté |
| functor | T\& | Un objet fonction auquel le delegate nouvellement construit pointera |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) méthode

Constructeur de déplacement. Construit un delegate à partir de l'objet fonction spécifié.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet fonction accepté par le constructeur comme argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| functor_tag | long | Une valeur entière factice ; cet argument est utilisé pour résoudre l'ambiguïté |
| functor | T\&& | Un objet fonction auquel le delegate nouvellement construit pointera |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) méthode

Constructeur. Construit un delegate qui pointe vers la méthode non statique spécifiée de l'objet spécifié.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| MemberType | type de la méthode non statique que le constructeur accepte comme argument |
| ClassType | type de l'objet accepté par le constructeur comme argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Un pointeur vers la méthode non statique que la nouvelle instance Delegate pointera |
| obj | ClassType * | Un pointeur vers un objet dont la méthode membre sera pointée par le nouveau delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) méthode

Constructeur. Construit un delegate qui pointe vers la méthode non statique spécifiée de l'objet spécifié.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| MemberType | type de la méthode non statique que le constructeur accepte comme argument |
| ClassType | type de l'objet accepté par le constructeur comme argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| member | MemberType MemberClass::* | Un pointeur vers la méthode non statique que la nouvelle instance Delegate pointera |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un pointeur partagé vers un objet dont la méthode membre sera pointée par le nouveau delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) méthode

Construit un objet delegate qui pointe vers un objet fonction std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| R | type de retour de l'objet fonction accepté par le constructeur comme argument |
| Args | liste d'arguments de l'objet fonction accepté par le constructeur comme argument |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Un objet fonction qui sera pointé par le nouvel objet delegate |

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Delegate< ReturnType(ArgumentTypes...)>](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)