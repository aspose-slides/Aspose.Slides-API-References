---
title: IModernComment
second_title: Aspose.Slides के लिए Java API रेफ़रेंस
description: स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imoderncomment/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Represents एक comment को slide पर दर्शाता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getShape()](#getShape--) | एक shape जो comment से जुड़ा है, लौटाता है। |
| [getTextSelectionStart()](#getTextSelectionStart--) | यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन की शुरुआती स्थिति को लौटाता है या सेट करता है। |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन की शुरुआती स्थिति को लौटाता है या सेट करता है। |
| [getTextSelectionLength()](#getTextSelectionLength--) | यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन लंबाई को लौटाता है या सेट करता है। |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन लंबाई को लौटाता है या सेट करता है। |
| [getStatus()](#getStatus--) | टिप्पणी की स्थिति को लौटाता है या सेट करता है। |
| [setStatus(byte value)](#setStatus-byte-) | टिप्पणी की स्थिति को लौटाता है या सेट करता है। |

### getShape() {#getShape--}
```
public abstract IShape getShape()
```

एक shape जो comment से जुड़ा है, लौटाता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)।

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन की शुरुआती स्थिति को लौटाता है या सेट करता है। पढ़ें/लिखें int।

**रिटर्न:**
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन की शुरुआती स्थिति को लौटाता है या सेट करता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन लंबाई को लौटाता है या सेट करता है। पढ़ें/लिखें int।

**रिटर्न:**
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

यदि comment AutoShape से जुड़ा है तो text frame में टेक्स्ट चयन लंबाई को लौटाता है या सेट करता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

टिप्पणी की स्थिति को लौटाता है या सेट करता है। पढ़ें/लिखें [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)।

**रिटर्न:**
byte

### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

टिप्पणी की स्थिति को लौटाता है या सेट करता है। पढ़ें/लिखें [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |