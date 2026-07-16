---
title: WriteRaw()
second_title: Référence API Aspose.Slides pour C++
description: Écrit du balisage brut manuellement à partir d'un tampon de caractères.
type: docs
weight: 417
url: /fr/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) méthode

Écrit du balisage brut manuellement à partir d'un tampon de caractères.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Tableau de caractères contenant le texte à écrire. |
| index | **int32_t** | La position dans le tampon indiquant le début du texte à écrire. |
| count | **int32_t** | Le nombre de caractères à écrire. |

## XmlTextWriter::WriteRaw(const String\&) méthode

Écrit du balisage brut manuellement à partir d'une chaîne.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) contenant le texte à écrire. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlTextWriter](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)