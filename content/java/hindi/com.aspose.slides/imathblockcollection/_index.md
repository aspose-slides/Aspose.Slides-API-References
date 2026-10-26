---
title: IMathBlockCollection
second_title: Aspose.Slides जावा API संदर्भ
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

## विधियां

| विधि | विवरण |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | संग्रह के अंत में IMathBlock जोड़ता है। |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | निर्दिष्ट अनुक्रमणिका पर संग्रह में IMathBlock सम्मिलित करता है। |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | संग्रह से एक विशिष्ट वस्तु की पहली उपस्थिति को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमणिका पर आइटम को हटाता है। |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | निश्चित करता है कि संग्रह में एक विशिष्ट मान मौजूद है या नहीं। |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | संग्रह में एक विशिष्ट IMathBlock का अनुक्रमणिका निर्धारित करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर आइटम प्राप्त करता है। |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | निर्दिष्ट अनुक्रमणिका पर आइटम प्राप्त करता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

संग्रह के अंत में IMathBlock जोड़ता है।

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | संग्रह के अंत में जोड़ा जाने वाला एक गणितीय ब्लॉक |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

निर्दिष्ट अनुक्रमणिका पर संग्रह में IMathBlock सम्मिलित करता है।

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
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ आइटम सम्मिलित किया जाना चाहिए। |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | सम्मिलित करने के लिये IMathBlock। |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

संग्रह से एक विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | संग्रह से हटाने वाला वस्तु। |

**वापसी:**
boolean - यदि आइटम को सफलतापूर्वक संग्रह से हटाया गया तो true; अन्यथा false। यदि आइटम मूल संग्रह में नहीं मिला तो भी यह मेथड false लौटाता है।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट अनुक्रमणिका पर आइटम को हटाता है।

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
| index | int | हटाने वाले आइटम की शून्य-आधारित अनुक्रमणिका। |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

निश्चित करता है कि संग्रह में एक विशिष्ट मान मौजूद है या नहीं।

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | संग्रह में खोजे जाने वाला वस्तु। |

**वापसी:**
boolean - यदि आइटम संग्रह में मिला तो true; अन्यथा false।

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

संग्रह में एक विशिष्ट IMMathBlock का अनुक्रमणिका निर्धारित करता है।

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | संग्रह में खोजे जाने वाला आइटम। |

**वापसी:**
int - यदि आइटम संग्रह में मिला तो उसका अनुक्रमणिका; अन्यथा -1।

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

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

निर्दिष्ट अनुक्रमणिका पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../com.aspose.slides/imathblock)।

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
| index | int | प्राप्त करने वाले आइटम की शून्य-आधारित अनुक्रमणिका। |

**वापसी:**
[IMathBlock](../../com.aspose.slides/imathblock) - एक गणितीय पाठ का ब्लॉक।

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

निर्दिष्ट अनुक्रमणिका पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../com.aspose.slides/imathblock)।

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
| index | int | सेट करने वाले आइटम की शून्य-आधारित अनुक्रमणिका। |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | एक गणितीय पाठ का ब्लॉक। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```