---
title: ISmartArtNodeCollection
second_title: Aspose.Slides for Java API संदर्भ
description: SmartArt नोड्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ismartartnodecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

SmartArt नोड्स का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | सूचकांक द्वारा नोड वापस करता है। |
| [addNode()](#addNode--) | नया नोड या उप-नोड जोड़ता है। |
| [removeNode(int index)](#removeNode-int-) | सूचकांक द्वारा नोड या उप-नोड हटाता है। |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | नोड या उप-नोड हटाता है। |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | नोड संग्रह में चयनित स्थिति पर नया नोड जोड़ता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


सूचकांक द्वारा नोड वापस करता है। केवल-पढ़ने-योग्य [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का शून्य-आधारित सूचकांक। |

**वापसी:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


नया नोड या उप-नोड जोड़ता है।

**वापसी:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


सूचकांक द्वारा नोड या उप-नोड हटाता है।

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नोड का शून्य-आधारित सूचकांक |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


नोड या उप-नोड हटाता है।

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | हटाने के लिए नोड। |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


नोड संग्रह में चयनित स्थिति पर नया नोड जोड़ता है।

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | नोड की शून्य-आधारित स्थिति। |

**वापसी:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड