---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Represents a gradient format.
type: docs
url: /hi/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

एक ग्रेडिएंट फ़ॉर्मेट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPosition()](#getPosition--) | एक ग्रेडिएंट स्टॉप की स्थिति (0..1) को लौटाता है या सेट करता है। |
| [setPosition(float value)](#setPosition-float-) | एक ग्रेडिएंट स्टॉप की स्थिति (0..1) को लौटाता है या सेट करता है। |
| [getColor()](#getColor--) | एक ग्रेडिएंट स्टॉप का रंग लौटाता है। |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


एक ग्रेडिएंट स्टॉप की स्थिति (0..1) को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**वापसी:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


एक ग्रेडिएंट स्टॉप की स्थिति (0..1) को लौटाता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


एक ग्रेडिएंट स्टॉप का रंग लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)