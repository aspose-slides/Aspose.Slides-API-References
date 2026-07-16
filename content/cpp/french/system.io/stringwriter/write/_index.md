---
title: Write()
second_title: Référence de l'API Aspose.Slides for C++ 
description: Écrit le caractère spécifié dans le flux.
type: docs
weight: 40
url: /fr/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) méthode

Écrit le caractère spécifié dans le flux.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | char_t | La valeur à écrire |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) méthode

Écrit la sous-plage spécifiée de caractères provenant du tableau de caractères spécifié dans le flux.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Le tableau contenant les caractères à écrire |
| index | **int32_t** | Un indice basé sur 0 de l’élément dans **buffer** où commence la sous-plage à écrire |
| count | **int32_t** | Le nombre de caractères dans la sous-plage à écrire |

## StringWriter::Write(const String\&) méthode

Écrit la chaîne spécifiée dans le flux.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La chaîne à écrire |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StringWriter](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)