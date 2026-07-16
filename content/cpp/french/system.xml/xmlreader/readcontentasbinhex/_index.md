---
title: ReadContentAsBinHex()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit le contenu et renvoie les octets binaires décodés en BinHex.
type: docs
weight: 781
url: /fr/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) méthode

Lit le contenu et renvoie les octets binaires décodes en **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tampon dans lequel copier le texte resultants. Cette valeur ne peut pas être **nullptr**. |
| index | **int32_t** | Le decalage dans le tampon ou commencer la copie du resultat. |
| count | **int32_t** | Le nombre maximal d'octets a copier dans le tampon. Le nombre reel d'octets copies est renvoye par cette methode. |

### Valeur de retour

Le nombre d'octets ecrits dans le tampon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliotheque [Aspose.Slides](../../../)