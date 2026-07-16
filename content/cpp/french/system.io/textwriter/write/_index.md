---
title: Write()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit la représentation sous forme de chaîne de l'objet spécifié dans le flux.
type: docs
weight: 105
url: /fr/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) méthode


Écrit la représentation sous forme de chaîne de l'objet spécifié dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'objet à écrire |

## TextWriter::Write(bool) méthode


Écrit la représentation sous forme de chaîne de la valeur booléenne spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **bool** | La valeur à écrire |

## TextWriter::Write(char_t) méthode


Écrit le caractère spécifié dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | char_t | La valeur à écrire |

## TextWriter::Write(Decimal) méthode


Écrit la représentation sous forme de chaîne de l'objet [Decimal](../../../system/decimal/) spécifié dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | L'objet à écrire |

## TextWriter::Write(double) méthode


Écrit la représentation sous forme de chaîne de la valeur à virgule flottante double précision spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | La valeur à écrire |

## TextWriter::Write(int) méthode


Écrit la représentation sous forme de chaîne de la valeur entière 32 bits spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | La valeur à écrire |

## TextWriter::Write(int64_t) méthode


Écrit la représentation sous forme de chaîne de la valeur entière 64 bits spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **int64_t** | La valeur à écrire |

## TextWriter::Write(float) méthode


Écrit la représentation sous forme de chaîne de la valeur à virgule flottante simple précision spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **float** | La valeur à écrire |

## TextWriter::Write(const String\&) méthode


Écrit la chaîne spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La chaîne à écrire |

## TextWriter::Write(uint32_t) méthode


Écrit la représentation sous forme de chaîne de la valeur entière non signée 32 bits spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | La valeur à écrire |

## TextWriter::Write(uint64_t) méthode


Écrit la représentation sous forme de chaîne de la valeur entière non signée 64 bits spécifiée dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | La valeur à écrire |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) méthode


Écrit tous les caractères du tableau spécifié dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Le tableau contenant les caractères à écrire |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) méthode


Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères spécifié dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Le tableau contenant les caractères à écrire |
| index | **int32_t** | Un indice basé sur 0 de l'élément dans **buffer** où commence la sous-plage à écrire |
| count | **int32_t** | Le nombre de caractères dans la sous-plage à écrire ; -1 indique que la sous-plage se termine à la fin du tableau **buffer** |

## TextWriter::Write(const char_t *) méthode


Écrit la chaîne C à écrire dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne C à écrire |

## TextWriter::Write(const TypeInfo\&) méthode


Écrit la représentation sous forme de chaîne de l'objet [TypeInfo](../../../system/typeinfo/) spécifié dans le flux.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | L'objet à écrire |

## TextWriter::Write(const String\&, const TArgs\&...) méthode


Écrit les valeurs spécifiées formatées selon le format spécifié dans le flux.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TArgs | La liste des types de valeurs à écrire |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Le format de chaîne |
| args | const TArgs\&... | Les valeurs à écrire |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [TextWriter](../)
* Classe [Decimal](../../../system/decimal/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)