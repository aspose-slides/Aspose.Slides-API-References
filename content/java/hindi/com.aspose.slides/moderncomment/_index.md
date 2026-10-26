---
title: ModernComment
second_title: Aspose.Slides for Java API संदर्भ
description: स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/moderncomment/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**सभी लागू इंटरफेस:**  
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject  
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।

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
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getShape()](#getShape--) | टिप्पणी से जुड़ा एक आकार लौटाता है। |
| [getTextSelectionStart()](#getTextSelectionStart--) | यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की शुरुआती स्थिति को प्राप्त करता है या सेट करता है। |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की शुरुआती स्थिति को प्राप्त करता है या सेट करता है। |
| [getTextSelectionLength()](#getTextSelectionLength--) | यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को प्राप्त करता है या सेट करता है। |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को प्राप्त करता है या सेट करता है। |
| [getStatus()](#getStatus--) | टिप्पणी की स्थिति को प्राप्त करता है या सेट करता है। |
| [setStatus(byte value)](#setStatus-byte-) | टिप्पणी की स्थिति को प्राप्त करता है या सेट करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

टिप्पणी से जुड़ा एक आकार लौटाता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape).

**वापसी:**  
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की शुरुआती स्थिति को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int.

**वापसी:**  
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की शुरुआती स्थिति को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int.

**वापसी:**  
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

यदि टिप्पणी AutoShape से संबंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

टिप्पणी की स्थिति को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**वापसी:**  
byte

### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

टिप्पणी की स्थिति को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject.

**वापसी:**  
com.aspose.slides.IDOMObject