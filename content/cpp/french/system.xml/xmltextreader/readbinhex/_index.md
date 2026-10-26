---
title: ReadBinHex()
second_title: Référence de l'API Aspose.Slides pour C++
description: Décode BinHex et renvoie les octets binaires décodés.
type: docs
weight: 781
url: /fr/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Décode **BinHex** et renvoie les octets binaires décodés.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets qui sert de tampon où les octets binaires décodés sont écrits. |
| offset | **int32_t** | L'index basé sur zéro dans le tableau indiquant où la méthode peut commencer à écrire dans le tampon. |
| len | **int32_t** | Le nombre d'octets à écrire dans le tampon. |

### Valeur de retour

Le nombre d'octets écrits dans votre tampon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlTextReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)