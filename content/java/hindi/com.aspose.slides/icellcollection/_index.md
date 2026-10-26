---
title: ICellCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: सेलों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icellcollection/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

सेलों का संग्रह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | सेल को उसकी स्थिति के आधार पर लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

सेल को उसकी स्थिति के आधार पर लौटाता है। केवल पढ़ने योग्य [ICell](../../com.aspose.slides/icell)।

--------------------

यदि सेल मिलाया गया हो तो कई इंडेक्स के लिए एक CellEx ऑब्जेक्ट लौटाया जा सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ICell](../../com.aspose.slides/icell)