---
title: ISmartArtNodeCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: SmartArt नोड्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ismartartnodecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

SmartArt नोड्स के संग्रह का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा नोड लौटाता है। |
| [addNode()](#addNode--) | नया नोड या उप-नोड जोड़ें। |
| [removeNode(int index)](#removeNode-int-) | इंडेक्स द्वारा नोड या उप-नोड हटाएँ। |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | नोड या उप-नोड हटाएँ। |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | नोड संग्रह में चयनित स्थिति में नया नोड जोड़ें। |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

इंडेक्स द्वारा नोड लौटाता है। केवल पढ़ने योग्य [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का शून्य-आधारित इंडेक्स। |

**रिटर्न:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)

### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

नया नोड या उप-नोड जोड़ें।

**रिटर्न:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड

### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

इंडेक्स द्वारा नोड या उप-नोड हटाएँ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नोड का शून्य-आधारित इंडेक्स |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

नोड या उप-नोड हटाएँ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | हटाने के लिए नोड। |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

नोड संग्रह में चयनित स्थिति में नया नोड जोड़ें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | शून्य-आधारित नोड स्थिति। |

**रिटर्न:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - जोड़ा गया नोड