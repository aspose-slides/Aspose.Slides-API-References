---
title: add method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Ajoute une nouvelle partie XML personnalisée.

### Renvoie

Partie XML personnalisée créée.



```python
def add(self, xml_data):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| xml_data | **bytes** | Les données XML de la nouvelle partie à ajouter. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData est `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData est vide ou invalide. |


## add(self, xml_string) {#str}
Ajoute une nouvelle partie XML personnalisée.

### Renvoie

Partie XML personnalisée créée.



```python
def add(self, xml_string):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| xml_string | **str** | La chaîne XML de la nouvelle partie à ajouter. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString est `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString est vide ou les données XML sont invalides. |


## add(self, input_stream) {#iorawiobase}
Ajoute une nouvelle partie XML personnalisée.

### Renvoie

Partie XML personnalisée créée.



```python
def add(self, input_stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Le flux d’entrée inputStream contenant les données XML de la nouvelle partie à ajouter. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream est `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Les données dans inputStream sont vides ou Sinvalid. |



### Voir aussi
* classe [`ICustomXmlPart`](/slides/python-net/fr/aspose.slides/icustomxmlpart)
* classe [`ICustomXmlPartCollection`](/slides/python-net/fr/aspose.slides/icustomxmlpartcollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)