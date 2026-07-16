---
title: BufferedStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un objet BufferedStream qui encapsule le flux spécifié et utilise un tampon de 4096 octets.
type: docs
weight: 1
url: /fr/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) constructeur


Construit un objet [BufferedStream](../) qui encapsule le flux spécifié et utilise un tampon de 4096 octets.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | L'objet sous-jacent [Stream](../../stream/) |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) constructeur


Construit un objet [BufferedStream](../) qui encapsule le flux spécifié et utilise un tampon de la taille spécifiée.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | L'objet sous-jacent [Stream](../../stream/) |
| bufferSize | int | La taille du tampon en octets |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BufferedStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)