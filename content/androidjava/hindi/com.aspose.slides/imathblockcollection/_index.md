---
title: IMathBlockCollection
second_title: Aspose.Slides for Android के लिये Java API संदर्भ
description: गणित ब्लॉकों का संग्रह IMathBlock
type: docs
url: /hi/com.aspose.slides/imathblockcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

गणित ब्लॉकों का संग्रह (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## मेथड्स

| Method | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | IMathBlock को संग्रह के अंत में जोड़ता है। |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | निर्दिष्ट इंडेक्स पर संग्रह में IMMathBlock डालता है। |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | संग्रह से किसी विशिष्ट वस्तु की प्रथम घटना हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संग्रह से एक आइटम हटाता है। |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | निर्धारित करता है कि क्या संग्रह में कोई विशिष्ट मान मौजूद है। |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | संग्रह में विशिष्ट IMathBlock का इंडेक्स निर्धारित करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। |
| [clear()](#clear--) | संग्रह से सभी तत्व हटाता है। |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

IMathBlock को संग्रह के अंत में जोड़ता है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | एक गणितीय ब्लॉक जो संग्रह के अंत में जोड़ दिया जाएगा। |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

निर्दिष्ट इंडेक्स पर संग्रह में IMathBlock डालता है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ आइटम डालना चाहिए। |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | डालने के लिए IMathBlock। |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

संग्रह से किसी विशिष्ट वस्तु की प्रथम घटना हटाता है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | संग्रह से हटाने के लिए वस्तु। |

**वापसी:**
boolean - यदि आइटम सफलतापूर्वक संग्रह से हटाया गया तो true; अन्यथा false। यदि मूल संग्रह में आइटम नहीं मिला तो भी यह मेथड false लौटाता है।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संग्रह से एक आइटम हटाता है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जिस पर आइटम हटाया जाना है। |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

निर्धारित करता है कि क्या संग्रह में कोई विशिष्ट मान मौजूद है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | संग्रह में खोजने के लिए वस्तु। |

**वापसी:**
boolean - true यदि आइटम संग्रह में पाया जाता है; अन्यथा false।

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

निर्धारित करता है कि संग्रह में विशिष्ट IMathBlock का इंडेक्स क्या है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | संग्रह में खोजने के लिए आइटम। |

**वापसी:**
int - यदि आइटम संग्रह में पाया जाता है तो उसका इंडेक्स; अन्यथा -1।

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../com.aspose.slides/imathblock)।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जिस पर आइटम प्राप्त करना है। |

**वापसी:**
[IMathBlock](../../com.aspose.slides/imathblock) - गणितीय पाठ का ब्लॉक।

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

निर्दिष्ट इंडेक्स पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../com.aspose.slides/imathblock)।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जिस पर आइटम सेट करना है। |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | गणितीय पाठ का ब्लॉक। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्व हटाता है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```