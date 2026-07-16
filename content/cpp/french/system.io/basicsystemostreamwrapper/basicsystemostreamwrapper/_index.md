---
title: BasicSystemOStreamWrapper()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance de BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /fr/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructeur


Construit une nouvelle instance de [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Le pointeur vers le flux |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Mode d’encapsulation |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) constructeur


Constructeur de copie. Supprimé.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) constructeur


Constructeur de déplacement.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) à déplacer |

## Voir aussi

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BasicSystemOStreamWrapper](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)