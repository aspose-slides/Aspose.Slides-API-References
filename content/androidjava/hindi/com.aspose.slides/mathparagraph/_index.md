---
title: MathParagraph
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: गणितीय पैराग्राफ जो गणितीय ब्लॉकों IMathBlock का कंटेनर है
type: docs
url: /hi/com.aspose.slides/mathparagraph/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject  
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

गणितीय पैराग्राफ जो गणितीय ब्लॉकों (IMathBlock) का कंटेनर है

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## कन्स्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | MathParagraph क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | MathParagraph क्लास का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getJustification()](#getJustification--) | पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate ऑब्जेक्ट लौटाता है। |
| [getCount()](#getCount--) | कलेक्शन में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। |
| [clear()](#clear--) | कलेक्शन से सभी तत्वों को हटाता है। |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | कलेक्शन के अंत में IMathBlock जोड़ता है। |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | कलेक्शन से विशिष्ट ऑब्जेक्ट की पहली घटना को हटाता है। |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | निर्धारित करता है कि कलेक्शन में एक विशिष्ट मान मौजूद है या नहीं। |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | कलेक्शन में विशिष्ट IMathBlock का इंडेक्स निर्धारित करता है। |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | निर्दिष्ट इंडेक्स पर कलेक्शन में IMathBlock सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन में निर्दिष्ट इंडेक्स पर आइटम हटाता है। |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | इस [MathParagraph](../../com.aspose.slides/mathparagraph) की सामग्री को MathML के रूप में सहेजता है। |
| [toLatex()](#toLatex--) | LaTeX स्वरूप में गणितीय समीकरण प्राप्त करता है। |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

MathParagraph क्लास का एक नया उदाहरण प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```

MathParagraph क्लास का एक नया उदाहरण प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**रिटर्न:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

पैराग्राफ संरेखण डिफ़ॉल्ट मान: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

कलेक्शन में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../com.aspose.slides/imathblock)।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | प्राप्त करने के लिए आइटम का शून्य-आधारित इंडेक्स |

**रिटर्न:**
[IMathBlock](../../com.aspose.slides/imathblock) - गणितीय पाठ का ब्लॉक।
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../com.aspose.slides/imathblock)।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | प्राप्त करने के लिए आइटम का शून्य-आधारित इंडेक्स |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | गणितीय पाठ का ब्लॉक। |

### clear() {#clear--}
```
public final void clear()
```

कलेक्शन से सभी तत्वों को हटाता है।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```

कलेक्शन के अंत में IMathBlock जोड़ता है।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | कलेक्शन के अंत में जोड़े जाने वाला गणितीय ब्लॉक |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

कलेक्शन से विशिष्ट ऑब्जेक्ट की पहली घटना को हटाता है।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | कलेक्शन से हटाने के लिए ऑब्जेक्ट। |

**रिटर्न:**
boolean - true यदि mathBlock को सफलतापूर्वक कलेक्शन से हटाया गया; अन्यथा false। यदि मूल कलेक्शन में mathBlock नहीं मिला तो भी यह false लौटाता है।
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

निर्धारित करता है कि कलेक्शन में एक विशिष्ट मान मौजूद है या नहीं।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | कलेक्शन में खोजा जाने वाला ऑब्जेक्ट। |

**रिटर्न:**
boolean - true यदि mathBlock कलेक्शन में पाया गया; अन्यथा false।
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

कलेक्शन में विशिष्ट IMathBlock का इंडेक्स निर्धारित करता है।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | कलेक्शन में खोजा जाने वाला आइटम। |

**रिटर्न:**
int - यदि mathBlock कलेक्शन में मिला तो उसका इंडेक्स; अन्यथा -1।
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

निर्दिष्ट इंडेक्स पर कलेक्शन में IMathBlock सम्मिलित करता है।

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित इंडेक्स जहाँ आइटम सम्मिलित किया जाना चाहिए। |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | सम्मिलित करने के लिए IMathBlock। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

कलेक्शन में निर्दिष्ट इंडेक्स पर आइटम हटाता है।

--------------------

> ```
> उदाहरण:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले आइटम का शून्य-आधारित इंडेक्स। |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**रिटर्न:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

इस [MathParagraph](../../com.aspose.slides/mathparagraph) की सामग्री को MathML के रूप में सहेजता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |

### toLatex() {#toLatex--}
```
public final String toLatex()
```

LaTeX स्वरूप में गणितीय समीकरण प्राप्त करता है

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**रिटर्न:**
java.lang.String