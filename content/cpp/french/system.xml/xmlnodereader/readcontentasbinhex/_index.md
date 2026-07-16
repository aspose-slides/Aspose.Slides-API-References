---
title: ReadContentAsBinHex()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit le contenu et renvoie les octets binaires décodés en BinHex.
type: docs
weight: 456
url: /fr/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) méthode

Lit le contenu et renvoie les octets binaires décodés en BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tampon dans lequel copier le texte résultant. Cette valeur ne peut pas être **nullptr**. |
| index | **int32_t** | Le décalage dans le tampon où commencer à copier le résultat. |
| count | **int32_t** | Le nombre maximal d'octets à copier dans le tampon. Le nombre réel d'octets copiés est renvoyé par cette méthode. |

### Valeur de retour

Le nombre d'octets écrits dans le tampon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)