---
title: WriteLine()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit les caractères de terminaison de ligne dans le flux.
type: docs
weight: 92
url: /fr/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() méthode

Écrit les caractères de terminaison de ligne dans le flux.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) méthode

Écrit la chaîne spécifiée suivie des caractères de terminaison de ligne dans le flux.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La chaîne à écrire |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) méthode

Écrit la représentation sous forme de chaîne de l'objet spécifié suivie des caractères de terminaison de ligne dans le flux.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'objet à écrire |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) méthode

Écrit tous les caractères du tableau spécifié suivis des caractères de terminaison de ligne dans le flux.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Le tableau contenant les caractères à écrire |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères spécifié suivie des caractères de terminaison de ligne dans le flux.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Le tableau contenant les caractères à écrire |
| index | **int32_t** | Un indice basé sur 0 de l'élément dans **buffer** où commence la sous-plage à écrire |
| count | **int32_t** | Le nombre de caractères dans la sous-plage à écrire ; -1 indique que la sous-plage se termine où le tableau **buffer** se termine |

## StreamWriter::WriteLine(const char_t *) méthode

Écrit la chaîne C spécifiée suivie des caractères de terminaison de ligne dans le flux.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const char_t * | La chaîne C à écrire |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) méthode

Écrit la représentation sous forme de chaîne de l'objet spécifié suivie des caractères de terminaison de ligne dans le flux.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | L'objet à écrire |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)