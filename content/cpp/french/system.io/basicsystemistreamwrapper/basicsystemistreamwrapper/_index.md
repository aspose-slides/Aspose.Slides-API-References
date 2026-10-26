---
title: BasicSystemIStreamWrapper()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance de BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /fr/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructeur

Construit une nouvelle instance de [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Le pointeur vers le flux |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Mode d'encapsulation |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) constructeur

Constructeur de copie. Supprimé.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) constructeur

Constructeur de déplacement.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) à déplacer |

## Voir aussi

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BasicSystemIStreamWrapper](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)