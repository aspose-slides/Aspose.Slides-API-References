---
title: MathBlock
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक MathParagraph के भीतर स्थित गणितीय पाठ का उदाहरण निर्दिष्ट करता है जो अपनी अलग पंक्ति पर शुरू होता है।
type: docs
url: /hi/com.aspose.slides/mathblock/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject  
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

एक गणितीय पाठ की उदाहरण को निर्दिष्ट करता है जो MathParagraph के भीतर होता है और अपनी स्वयं की पंक्ति पर शुरू होता है। सभी गणितीय ज़ोन, जिसमें समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों के एरे, और फ़ॉर्मूले शामिल हैं, को math block द्वारा दर्शाया जाता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [MathBlock()](#MathBlock--) | MathBlock क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व उसमें रखता है। |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्वों को इसमें रखता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | कलेक्शन में वास्तविक रूप से मौजूद चाइल्ड गणित तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर IMathElement को प्राप्त या सेट करता है। |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | निर्दिष्ट इंडेक्स पर IMathElement को प्राप्त या सेट करता है। |
| [isReadOnly()](#isReadOnly--) | false लौटाता है क्योंकि चाइल्ड एलिमेंट्स का कलेक्शन संशोधित किया जा सकता है। |
| [getChildren()](#getChildren--) | बच्चे तत्व प्राप्त करें |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate ऑब्जेक्ट लौटाता है। |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | गणितीय तत्व को कलेक्शन के अंत में जोड़ता है। |
| [clear()](#clear--) | कलेक्शन से सभी तत्वों को हटाता है। |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | निर्धारित करता है कि कलेक्शन में कोई विशिष्ट मान है या नहीं। |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | निर्दिष्ट एरे में कॉपी करता है। |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | कलेक्शन से विशिष्ट ऑब्जेक्ट की पहली घटना को हटाता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटरेट करने वाला इनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक java इटररेटर लौटाता है। |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | कलेक्शन में विशिष्ट गणितीय तत्व का इंडेक्स निर्धारित करता है। |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | निर्दिष्ट इंडेक्स पर MathElement को कलेक्शन में डालता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन के निर्दिष्ट इंडेक्स पर तत्व हटाता है। |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | एक गणितीय तत्व को इस गणितीय ब्लॉक के साथ जोड़ता है। |
| [join(String mathText)](#join-java.lang.String-) | एक गणितीय पाठ को इस गणितीय ब्लॉक के साथ जोड़ता है। |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | एक अन्य गणितीय ब्लॉक को इस के साथ जोड़ता है। |
| [delimit(char separatorCharacter)](#delimit-char-) | बिना कोष्ठकों के, सेपरटर कैरेक्टर के साथ चाइल्ड एलिमेंट्स को सीमित करता है। |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | इस ब्लॉक के चाइल्ड एलिमेंट्स को निर्दिष्ट कैरेक्टर्स जैसे कोष्ठक या अन्य कैरेक्टर्स में फ्रेमिंग के रूप में संलग्न करता है। |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | इस ब्लॉक के चाइल्ड एलिमेंट्स को निर्दिष्ट कैरेक्टर्स जैसे कोष्ठक या अन्य में फ्रेमिंग के रूप में संलग्न करता है और सेपरटर कैरेक्टर से सीमित करता है। |
| [toMathArray()](#toMathArray--) | चाइल्ड एलिमेंट्स को एक वर्टिकल एरे में रखता है। |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | [MathBlock](../../com.aspose.slides/mathblock) की सामग्री को MathML के रूप में सहेजता है। |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

MathBlock क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व उसमें रखता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | ब्लॉक में रखने के लिए गणितीय तत्व |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्वों को इसमें रखता है।

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**पैरामीटर:**
| पैरामी्टर | प्रकार | विवरण |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | ब्लॉक में रखने के लिए गणितीय तत्व |

### getCount() {#getCount--}
```
public final int getCount()
```

कलेक्शन में वास्तविक रूप से मौजूद चाइल्ड गणित तत्वों की संख्या प्राप्त करता है। केवल- पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**रिटर्न्स:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

निर्दिष्ट इंडेक्स पर IMathElement को प्राप्त या सेट करता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | आइटम का शून्य-आधारित इंडेक्स |

**रिटर्न्स:**
[IMathElement](../../com.aspose.slides/imathelement) - गणितीय तत्व।
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

निर्दिष्ट इंडेक्स पर IMathElement को प्राप्त या सेट करता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | आइटम का शून्य-आधारित इंडेक्स |
| value | [IMathElement](../../com.aspose.slides/imathelement) | गणितीय तत्व। |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

false लौटाता है क्योंकि चाइल्ड एलिमेंट्स का कलेक्शन संशोधित किया जा सकता है।

**रिटर्न्स:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बच्चे तत्व प्राप्त करें

**रिटर्न्स:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल- पढ़ने योग्य IDOMObject।

**रिटर्न्स:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

गणितीय तत्व को कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | कलेक्शन के अंत में जोड़े जाने वाला IMathElement। |
### clear() {#clear--}
```
public final void clear()
```

कलेक्शन से सभी तत्वों को हटाता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

निर्धारित करता है कि कलेक्शन में कोई विशिष्ट मान है या नहीं।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | कलेक्शन में खोजे जाने वाला ऑब्जेक्ट। |

**रिटर्न्स:**
boolean - यदि item कलेक्शन में पाया गया तो true; अन्यथा false।
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

निर्दिष्ट एरे में कॉपी करता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | कॉपी करने के लिए एरे। |
| arrayIndex | int | कॉपी शुरू करने का इंडेक्स। |
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

कलेक्शन से विशिष्ट ऑब्जेक्ट की पहली घटना को हटाता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | कलेक्शन से हटाने वाला ऑब्जेक्ट। |

**रिटर्न्स:**
boolean - यदि item कलेक्शन से सफलतापूर्वक हटाया गया तो true; अन्यथा false। यह मेथड तब भी false लौटाता है जब मूल कलेक्शन में item नहीं मिला।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

कलेक्शन के माध्यम से इटरेट करने वाला इनेमरेटर लौटाता है।

**रिटर्न्स:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - एक IGenericEnumerator जिसका उपयोग कलेक्शन को इटरेट करने के लिए किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

पूरे कलेक्शन के लिए एक java इटररेटर लौटाता है।

**रिटर्न्स:**
com.aspose.ms.System.Collections.IEnumerator - पूरे कलेक्शन के लिए एक java.util.Iterator।
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

कलेक्शन में विशिष्ट गणितीय तत्व का इंडेक्स निर्धारित करता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | कलेक्शन में खोजे जाने वाला तत्व। |

**रिटर्न्स:**
int - यदि item कलेक्शन में पाया गया तो उसका इंडेक्स; अन्यथा -1।
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

निर्दिष्ट इंडेक्स पर MathElement को कलेक्शन में डालता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | MathElement को डालने के लिए शून्य-आधारित इंडेक्स। |
| item | [IMathElement](../../com.aspose.slides/imathelement) | डालने के लिए MathElement। |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर कलेक्शन में तत्व को हटाता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित इंडेक्स। |
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

गणितीय तत्व को इस गणितीय ब्लॉक के साथ जोड़ता है।

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | जोड़ने के लिए तत्व। |

**रिटर्न्स:**
[IMathBlock](../../com.aspose.slides/imathblock) - वर्तमान IMathBlock का इंस्टेंस
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

गणितीय पाठ को इस गणितीय ब्लॉक के साथ जोड़ता है।

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | जोड़ने के लिए गणितीय पाठ। |

**रिटर्न्स:**
[IMathBlock](../../com.aspose.slides/imathblock) - इस इंस्टेंस और निर्दिष्ट आर्ग्यूमेंट को शामिल करता नया IMathBlock
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

एक अन्य गणितीय ब्लॉक को इस के साथ जोड़ता है।

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | जोड़ने वाला ब्लॉक। |

**रिटर्न्स:**
[IMathBlock](../../com.aspose.slides/imathblock) - जुड़ने के बाद यह गणितीय ब्लॉक
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

बिना कोष्ठकों के, सेपरटर कैरेक्टर के साथ चाइल्ड एलिमेंट्स को सीमित करता है।

--------------------

> ```
> उदाहरण:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char | सेपरटर कैरेक्टर। |

**रिटर्न्स:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

इस ब्लॉक के चाइल्ड एलिमेंट्स को निर्दिष्ट कैरेक्टर्स जैसे कोष्ठक या अन्य कैरेक्टर्स में फ्रेमिंग के रूप में संलग्न करता है।

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारंभिक कैरेक्टर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | अंतिम कैरेक्टर (आमतौर पर दायाँ कोष्ठक) |

**रिटर्न्स:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें निर्दिष्ट कैरेक्टर्स फ्रेमिंग के रूप में शामिल हैं।
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

इस ब्लॉक के चाइल्ड एलिमेंट्स को निर्दिष्ट कैरेक्टर्स जैसे कोष्ठक या अन्य में फ्रेमिंग के रूप में संलग्न करता है और सेपरटर कैरेक्टर से सीमित करता है।

--------------------

> ```
> उदाहरण:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारंभिक कैरेक्टर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | अंतिम कैरेक्टर (आमतौर पर दायाँ कोष्ठक) |
| separatorCharacter | char | सेपरटर कैरेक्टर। |

**रिटर्न्स:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें निर्दिष्ट कैरेक्टर्स फ्रेमिंग और डेलीमिटर के रूप में शामिल हैं।
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

चाइल्ड एलिमेंट्स को एक वर्टिकल एरे में रखता है।

--------------------

> ```
> उदाहरण:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**रिटर्न्स:**
[IMathArray](../../com.aspose.slides/imatharray) - प्रकार [IMathArray](../../com.aspose.slides/imatharray) की नई इंस्टेंस
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

[MathBlock](../../com.aspose.slides/mathblock) की सामग्री को MathML के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |