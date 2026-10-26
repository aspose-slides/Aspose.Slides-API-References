---
title: ICellCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: सेल्स के एक संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icellcollection/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

सेल्स का एक संग्रह दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | सेल को उसकी स्थिति से वापस करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

सेल को उसकी स्थिति से वापस करता है। केवल-पढ़ने योग्य [ICell](../../com.aspose.slides/icell)।

--------------------

यदि सेल मर्ज किया गया हो तो कई इंडेक्स के लिए एक CellEx ऑब्जेक्ट लौटाया जा सकता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ICell](../../com.aspose.slides/icell)