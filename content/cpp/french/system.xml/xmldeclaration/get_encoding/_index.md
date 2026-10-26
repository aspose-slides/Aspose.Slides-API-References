---
title: get_Encoding()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le niveau d'encodage du document XML.
type: docs
weight: 14
url: /fr/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() méthode


Renvoie le niveau d'encodage du document XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### Valeur de retour

Le nom d'encodage de caractères valide.
## Remarques



Les noms d'encodage de caractères les plus couramment pris en charge pour XML sont les suivants :

| Catégorie | Noms d'encodage |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (où "n" est un chiffre de 1 à 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |


Cette valeur est facultative. Si aucune valeur n'est définie, cette méthode renvoie [String::Empty](../../../system/string/empty/). Si un attribut d'encodage n'est pas inclus, l'encodage UTF-8 est supposé lorsque le document est écrit ou enregistré. 
## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlDeclaration](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)