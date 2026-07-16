---
title: WriteRaw()
second_title: Référence API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, écrit du balisage brut manuellement à partir d'un tampon de caractères.
type: docs
weight: 287
url: /fr/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) méthode

Lorsqu'elle est remplacée dans une classe dérivée, écrit du balisage brut manuellement à partir d'un tampon de caractères.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Tableau de caractères contenant le texte à écrire. |
| index | **int32_t** | La position dans le tampon indiquant le début du texte à écrire. |
| count | **int32_t** | Le nombre de caractères à écrire. |

## XmlWriter::WriteRaw(const String\&) méthode

Lorsqu'elle est remplacée dans une classe dérivée, écrit du balisage brut manuellement à partir d'une chaîne.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) contenant le texte à écrire. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)