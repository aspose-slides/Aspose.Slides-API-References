---
title: BinaryWriter()
second_title: Référence de l'API Aspose.Slides for C++
description: Construit une instance de la classe BinaryWriter qui écrit des données dans le flux spécifié en utilisant le codage spécifié.
type: docs
weight: 1
url: /fr/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructeur

Construit une instance de la classe [BinaryWriter](../) qui écrit des données dans le flux spécifié en utilisant le codage spécifié.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Le flux de sortie |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage à utiliser |
| leaveopen | **bool** | Indique si le flux **stream** doit rester ouvert (true) après que l'objet courant a été libéré ou non (false) |

## Voir aussi

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)