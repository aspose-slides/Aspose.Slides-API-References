---
title: Write()
second_title: Référence API Aspose.Slides pour C++
description: Écrit la valeur entière non signée de 8 bits spécifiée dans le flux de sortie.
type: docs
weight: 92
url: /fr/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) méthode

Écrit la valeur entière non signée de 8 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint8_t** | La valeur à écrire |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) méthode

Écrit la sous-plage spécifiée d'octets du tableau d'octets indiqué dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire |
| index | int | Un indice basé sur 0 de l'élément dans **buffer** où commence la sous-plage à écrire |
| count | int | Le nombre d'éléments dans la sous-plage à écrire ; -1 indique que la sous-plage se termine à la fin du tableau **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) méthode

Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères indiqué dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Le tableau contenant les caractères à écrire |
| index | int | Un indice basé sur 0 de l'élément dans **buffer** où commence la sous-plage à écrire |
| count | int | Le nombre de caractères dans la sous-plage à écrire ; -1 indique que la sous-plage se termine à la fin du tableau **buffer** |

## BinaryWriter::Write(bool) méthode

Écrit un octet unique valant 0 si **value** est vrai et 1 si **value** est faux dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **bool** | La valeur booléenne indiquant la valeur de l'octet à écrire dans le flux de sortie |

## BinaryWriter::Write(char16_t) méthode

Écrit la valeur du caractère sur 16 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | char16_t | La valeur à écrire |

## BinaryWriter::Write(int16_t) méthode

Écrit la valeur entière de 16 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **int16_t** | La valeur à écrire |

## BinaryWriter::Write(int) méthode

Écrit la valeur entière de 32 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | La valeur à écrire |

## BinaryWriter::Write(int64_t) méthode

Écrit la valeur entière de 64 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **int64_t** | La valeur à écrire |

## BinaryWriter::Write(uint16_t) méthode

Écrit la valeur entière non signée de 16 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint16_t** | La valeur à écrire |

## BinaryWriter::Write(uint32_t) méthode

Écrit la valeur entière non signée de 32 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | La valeur à écrire |

## BinaryWriter::Write(uint64_t) méthode

Écrit la valeur entière non signée de 64 bits spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | La valeur à écrire |

## BinaryWriter::Write(float) méthode

Écrit la valeur en virgule flottante simple précision spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **float** | La valeur à écrire |

## BinaryWriter::Write(double) méthode

Écrit la valeur en virgule flottante double précision spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | La valeur à écrire |

## BinaryWriter::Write(const Decimal\&) méthode

Écrit la représentation binaire de la valeur [Decimal](../../../system/decimal/) spécifiée dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | La valeur à écrire |

## BinaryWriter::Write(const String\&) méthode

Écrit une chaîne préfixée de sa longueur dans l'encodage actuel dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La chaîne à écrire |

## BinaryWriter::Write(const char_t *) méthode

Écrit une chaîne préfixée de sa longueur dans l'encodage actuel dans le flux de sortie.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | Le c-string à écrire |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)