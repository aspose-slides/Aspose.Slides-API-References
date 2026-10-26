---
title: BasicSystemIOStreamBuf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /fr/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() constructeur


Construit une nouvelle instance de [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) constructeur


Construit une nouvelle instance de [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Pointeur intelligent vers le flux |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Mode d'enveloppement |
| locale | const std::locale\& | locale de [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) constructeur


Constructeur de copie. Supprimé.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) constructeur


Constructeur de déplacement.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) à déplacer |

## Voir aussi

* Énum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [BasicSystemIOStreamBuf](../)
* Classe [Stream](../../stream/)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)