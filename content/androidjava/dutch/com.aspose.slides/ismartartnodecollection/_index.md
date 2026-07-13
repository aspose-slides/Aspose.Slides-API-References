---
title: ISmartArtNodeCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van SmartArt-knooppunten voor.
type: docs
url: /nl/com.aspose.slides/ismartartnodecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Stelt een collectie van SmartArt-knooppunten voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert knooppunt op index. |
| [addNode()](#addNode--) | Voeg nieuw knooppunt of subknooppunt toe. |
| [removeNode(int index)](#removeNode-int-) | Verwijder knooppunt of subknooppunt op index. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Verwijder knooppunt of subknooppunt. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Voeg nieuw knooppunt toe in de geselecteerde positie van de knooppuntencollectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Retourneert knooppunt op index. Alleen-lezen [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het element. |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Voeg nieuw knooppunt of subknooppunt toe.

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Toegevoegd knooppunt
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Verwijder knooppunt of subknooppunt op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nul-gebaseerde index van knooppunt |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Verwijder knooppunt of subknooppunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Te verwijderen knooppunt. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Voeg nieuw knooppunt toe in de geselecteerde positie van de knooppuntencollectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | Nul-gebaseerde knooppuntpositie. |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Toegevoegd knooppunt