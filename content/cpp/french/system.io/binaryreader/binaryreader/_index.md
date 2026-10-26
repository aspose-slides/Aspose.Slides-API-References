---
title: BinaryReader()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une instance de la classe BinaryReader qui lit les données du flux spécifié en utilisant l'encodage UTF-8.
type: docs
weight: 1
url: /fr/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructeur

Construit une instance de la classe [BinaryReader](../) qui lit les données du flux spécifié en utilisant l'encodage UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux d'entrée |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructeur

Construit une instance de la classe [BinaryReader](../) qui lit les données du flux spécifié en utilisant l'encodage spécifié.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux d'entrée |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | L'encodage à utiliser |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructeur

Construit une instance de la classe [BinaryReader](../) qui lit les données du flux spécifié en utilisant l'encodage spécifié.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux d'entrée |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | L'encodage à utiliser |
| leaveOpen | **bool** | Spécifie si le flux **input** doit rester ouvert (true) après que l'objet actuel a été libéré ou non (false) |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BinaryReader](../)
* Classe [Encoding](../../../system.text/encoding/)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)