---
title: ICustomXmlPartCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de parties xml personnalisées.
type: docs
url: /fr/com.aspose.slides/icustomxmlpartcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Représente une collection de parties xml personnalisées.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'élément à l'index spécifié. |
| [add(byte[] xmlData)](#add-byte---) | Ajoute une nouvelle partie xml personnalisée. |
| [add(String xmlString)](#add-java.lang.String-) | Ajoute une nouvelle partie xml personnalisée. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Ajoute une nouvelle partie xml personnalisée. |
| [removeAt(int index)](#removeAt-int-) | Supprime la partie xml personnalisée à l'index spécifié. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


Renvoie l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à récupérer. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - L'élément à l'index spécifié.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


Ajoute une nouvelle partie xml personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | Les données xml de la nouvelle partie à ajouter. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Partie xml personnalisée créée.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


Ajoute une nouvelle partie xml personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | La chaîne xml de la nouvelle partie à ajouter. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Partie xml personnalisée créée.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


Ajoute une nouvelle partie xml personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Le flux d'entrée contenant les données xml de la nouvelle partie à ajouter. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Partie xml personnalisée créée.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime la partie xml personnalisée à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


Supprime la première occurrence d'un objet spécifique de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | La partie xml personnalisée à supprimer. |

**Renvoie :**
boolean - true si l'élément a été supprimé avec succès ; sinon, false.
### clear() {#clear--}
```
public abstract void clear()
```


Supprime tous les éléments de la collection.