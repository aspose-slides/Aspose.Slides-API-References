---
title: StreamReader()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une instance de l'objet StreamReader qui lit des caractères à partir du flux sous-jacent spécifié en utilisant le codage UTF-8 et un tampon d'une taille par défaut de 1024 octets.
type: docs
weight: 1
url: /fr/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du flux sous-jacent spécifié en utilisant le codage UTF-8 et un tampon d'une taille par défaut de 1024 octets.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent à partir duquel lire les caractères |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du flux sous-jacent spécifié en utilisant le codage UTF-8 et un tampon d'une taille par défaut de 1024 octets. Un paramètre indique si la détection du marqueur d'ordre des octets doit être activée.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent à partir duquel lire les caractères |
| detectEncodingFromByteOrderMarks | **bool** | True pour rechercher les marqueurs d'ordre des octets au début du flux, sinon false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du flux sous-jacent spécifié en utilisant le codage spécifié et un tampon d'une taille par défaut de 1024 octets.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent à partir duquel lire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage à utiliser |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du flux sous-jacent spécifié en utilisant le codage spécifié et un tampon d'une taille par défaut de 1024 octets. Un paramètre indique si la détection du marqueur d'ordre des octets doit être activée.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent à partir duquel lire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage à utiliser |
| detectEncodingFromByteOrderMarks | **bool** | True pour rechercher les marqueurs d'ordre des octets au début du flux, sinon false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du flux sous-jacent spécifié en utilisant le codage spécifié et un tampon de la taille spécifiée. Un paramètre indique si la détection du marqueur d'ordre des octets doit être activée.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Le flux sous-jacent à partir duquel lire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage à utiliser |
| detectEncodingFromByteOrderMarks | **bool** | True pour rechercher les marqueurs d'ordre des octets au début du flux, sinon false |
| bufferSize | int | La taille minimale du tampon en octets |

## StreamReader::StreamReader(const System::String\&) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du fichier spécifié en utilisant le codage UTF-8 et un tampon d'une taille par défaut de 4096 octets.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Le chemin du fichier à partir duquel lire les caractères |

## StreamReader::StreamReader(const System::String\&, bool) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du fichier spécifié en utilisant le codage UTF-8 et un tampon d'une taille par défaut de 4096 octets. Un paramètre indique si la détection du marqueur d'ordre des octets doit être activée.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Le chemin du fichier à partir duquel lire les caractères |
| detectEncodingFromByteOrderMarks | **bool** | True pour rechercher les marqueurs d'ordre des octets au début du fichier, sinon false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du fichier spécifié en utilisant le codage spécifié et un tampon d'une taille par défaut de 4096 octets.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Le chemin du fichier à partir duquel lire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage à utiliser |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du flux sous-jacent spécifié en utilisant le codage spécifié et un tampon d'une taille par défaut de 4096 octets. Un paramètre indique si la détection du marqueur d'ordre des octets doit être activée.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Le chemin du fichier à partir duquel lire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage à utiliser |
| detectEncodingFromByteOrderMarks | **bool** | True pour rechercher les marqueurs d'ordre des octets au début du fichier, sinon false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor

Construit une instance de l'objet [StreamReader](../) qui lit des caractères à partir du fichier spécifié en utilisant le codage spécifié et un tampon de la taille spécifiée. Un paramètre indique si la détection du marqueur d'ordre des octets doit être activée.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Le chemin du fichier à partir duquel lire les caractères |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage à utiliser |
| detectEncodingFromByteOrderMarks | **bool** | True pour rechercher les marqueurs d'ordre des octets au début du fichier, sinon false |
| bufferSize | int | La taille minimale du tampon en octets |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)