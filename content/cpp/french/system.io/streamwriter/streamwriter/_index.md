---
title: StreamWriter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une instance de l'objet StreamWriter qui écrit des caractères sur le flux sous-jacent spécifié en utilisant l'encodage UTF-8 et un tampon d'une taille par défaut de 1024 octets.
type: docs
weight: 1
url: /fr/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructeur

Construit une instance de l'objet [StreamWriter](../) qui écrit des caractères sur le flux sous-jacent spécifié en utilisant l'encodage UTF-8 et un tampon de taille par défaut de 1024 octets.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent sur lequel écrire les caractères |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructeur

Construit une instance de l'objet [StreamWriter](../) qui écrit des caractères sur le flux sous-jacent spécifié en utilisant l'encodage spécifié et un tampon de taille par défaut de 1024 octets.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent sur lequel écrire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | L'encodage à utiliser |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructeur

Construit une instance de l'objet [StreamWriter](../) qui écrit des caractères sur le flux sous-jacent spécifié en utilisant l'encodage spécifié et un tampon de la taille spécifiée. Un paramètre indique si le flux sous-jacent doit être fermé lorsque l'objet [StreamWriter](../) est libéré.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent sur lequel écrire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | L'encodage à utiliser |
| buffer_size | int | La taille minimale du tampon en octets |
| leave_open | **bool** | Indique si le flux sous-jacent doit rester ouvert après que l'objet [StreamWriter](../) actuel soit libéré |

## StreamWriter::StreamWriter(const String\&) constructeur

Construit une instance de l'objet [StreamWriter](../) qui écrit des caractères dans le fichier spécifié en utilisant l'encodage UTF-8 et un tampon de taille par défaut de 1024 octets.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier dans lequel écrire les caractères |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructeur

Construit une instance de l'objet [StreamWriter](../) qui écrit des caractères dans le fichier spécifié en utilisant l'encodage spécifié et un tampon de taille par défaut de 1024 octets. Un paramètre indique si les données doivent être ajoutées au fichier ou si le fichier doit être écrasé.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier dans lequel écrire les caractères |
| append | **bool** | Indique si les données doivent être ajoutées au fichier spécifié (true) ou si le fichier doit être écrasé (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | L'encodage à utiliser |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructeur

Construit une instance de l'objet [StreamWriter](../) qui écrit des caractères dans le fichier spécifié en utilisant l'encodage spécifié et la taille du tampon. Un paramètre indique si les données doivent être ajoutées au fichier ou si le fichier doit être écrasé.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier dans lequel écrire les caractères |
| append | **bool** | Indique si les données doivent être ajoutées au fichier spécifié (true) ou si le fichier doit être écrasé (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | L'encodage à utiliser |
| buffer_size | int | La taille du tampon à utiliser |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)