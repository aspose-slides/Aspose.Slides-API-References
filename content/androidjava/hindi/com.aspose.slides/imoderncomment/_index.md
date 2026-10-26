---
title: IModernComment
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: एक स्लाइड पर टिप्पणी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imoderncomment/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

एक स्लाइड पर टिप्पणी का प्रतिनिधित्व करता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## विधियां

| विधि | विवरण |
| --- | --- |
| [getShape()](#getShape--) | टिप्पणी से संबंधित आकार को लौटाता है। |
| [getTextSelectionStart()](#getTextSelectionStart--) | यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की आरंभिक स्थिति को लौटाता है या सेट करता है। |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की आरंभिक स्थिति को लौटाता है या सेट करता है। |
| [getTextSelectionLength()](#getTextSelectionLength--) | यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को लौटाता है या सेट करता है। |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को लौटाता है या सेट करता है। |
| [getStatus()](#getStatus--) | टिप्पणी की स्थिति को लौटाता है या सेट करता है। |
| [setStatus(byte value)](#setStatus-byte-) | टिप्पणी की स्थिति को लौटाता है या सेट करता है। |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

टिप्पणी के साथ जुड़ा हुआ आकार लौटाता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)।

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की आरंभिक स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की आरंभिक स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

यदि टिप्पणी AutoShape के साथ जुड़ी हो तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

टिप्पणी की स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)।

**रिटर्न:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

टिप्पणी की स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |