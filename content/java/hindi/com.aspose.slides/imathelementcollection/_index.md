---
title: IMathElementCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: गणितीय तत्वों MathElement का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imathelementcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

गणितीय तत्वों (MathElement) का एक संग्रह दर्शाता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
```
## विधियां

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | गणितीय तत्व को संग्रह के अंत में जोड़ता है। |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | संग्रह में किसी विशिष्ट गणितीय तत्व का सूचकांक निर्धारित करता है। |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | निर्दिष्ट सूचकांक पर गणितीय तत्व को संग्रह में सम्मिलित करता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | निर्धारित करता है कि संग्रह में कोई विशिष्ट मान मौजूद है या नहीं। |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | संग्रह से किसी विशिष्ट वस्तु की पहली आवृत्ति को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर संग्रह में तत्व को हटाता है। |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | निर्दिष्ट एरे में कॉपी करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [IMathElement](../../com.aspose.slides/imathelement)।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | आइटम प्राप्त करने के लिए शून्य-आधारित सूचकांक। |

**वापसी मान:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**वापसी मान:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

संग्रह के अंत में एक गणितीय तत्व जोड़ता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह के अंत में जोड़ने के लिए IMathElement। |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

संग्रह में किसी विशिष्ट गणितीय तत्व का सूचकांक निर्धारित करता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह में स्थित तत्व। |

**वापसी मान:**
int - यदि तत्व संग्रह में पाया जाए तो उसका सूचकांक; अन्यथा, -1।
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

निर्दिष्ट सूचकांक पर गणितीय तत्व को संग्रह में सम्मिलित करता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंसर्ट करने के लिए शून्य-आधारित सूचकांक जहाँ IMMathElement सम्मिलित किया जाना चाहिए। |
| item | [IMathElement](../../com.aspose.slides/imathelement) | इंसर्ट करने के लिए IMathElement। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

निर्धारित करता है कि संग्रह में कोई विशिष्ट मान मौजूद है या नहीं।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह में स्थित वस्तु। |

**वापसी मान:**
boolean - यदि वस्तु संग्रह में पाई जाती है तो true; अन्यथा false।
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

संग्रह से किसी विशिष्ट वस्तु की पहली आवृत्ति को हटाता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह से हटाने वाली वस्तु। |

**वापसी मान:**
boolean - यदि वस्तु सफलतापूर्वक हटाई गई हो तो true; अन्यथा false. यह मेथड तब भी false लौटाता है जब मूल संग्रह में वस्तु नहीं पाई जाती।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए तत्व का शून्य-आधारित सूचकांक। |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

निर्दिष्ट एरे में कॉपी करता है।

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | कॉपी करने के लिए एरे। |
| arrayIndex | int | कॉपी शुरू करने के लिए सूचकांक। |