---
title: IPointCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: भागों का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipointcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

भागों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में बिंदुओं की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर बिंदु लौटाता है। |

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में बिंदुओं की संख्या लौटाता है। केवल पढ़ने योग्य int।

**वापसी:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर बिंदु लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का अनुक्रमांक। |

**वापसी:**
[IPoint](../../com.aspose.slides/ipoint) - यह [IPoint](../../com.aspose.slides/ipoint) ऑब्जेक्ट।