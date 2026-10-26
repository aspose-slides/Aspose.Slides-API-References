---
title: MathBlock
second_title: Aspose.Slides के लिए Java API संदर्भ
description: MathParagraph के भीतर स्थित गणितीय पाठ के एक उदाहरण को निर्दिष्ट करता है और यह अपनी स्वयं की पंक्ति से शुरू होता है।
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

एक MathParagraph के भीतर स्थित गणितीय पाठ के एक उदाहरण को निर्दिष्ट करता है जो अपनी स्वयं की पंक्ति से शुरू होता है। सभी गणितीय क्षेत्र, जैसे समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों की सरणियाँ, और सूत्र, math block द्वारा प्रतिनिधित्व किए जाते हैं।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [MathBlock()](#MathBlock--) | MathBlock क्लास का नया उदाहरण आरंभ करता है। |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व को इसमें रखता है। |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्वों को इसमें रखता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में वास्तविक रूप से उपस्थित चाइल्ड गणित तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर IMathElement को प्राप्त या सेट करता है। |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | निर्दिष्ट अनुक्रमांक पर IMathElement को प्राप्त या सेट करता है। |
| [isReadOnly()](#isReadOnly--) | false लौटाता है क्योंकि चाइल्ड तत्वों का संग्रह संशोधित किया जा सकता है। |
| [getChildren()](#getChildren--) | चाइल्ड तत्व प्राप्त करें |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate ऑब्जेक्ट लौटाता है। |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | गणितीय तत्व को संग्रह के अंत में जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | निर्धारित करता है कि क्या संग्रह में एक विशिष्ट मान मौजूद है। |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | निर्दिष्ट सरणी में कॉपी करता है। |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | संग्रह से विशिष्ट वस्तु की पहली उपस्थिति को हटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | संपूर्ण संग्रह के लिए जावा इटरेटर लौटाता है। |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | संग्रह में विशिष्ट गणितीय तत्व का अनुक्रमांक निर्धारित करता है। |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | निर्दिष्ट अनुक्रमांक पर संग्रह में MathElement डालता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह के निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | एक गणितीय तत्व को इस गणितीय ब्लॉक के साथ जोड़ता है। |
| [join(String mathText)](#join-java.lang.String-) | गणितीय पाठ को इस गणितीय ब्लॉक के साथ जोड़ता है। |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | एक और गणितीय ब्लॉक को इसके साथ जोड़ता है। |
| [delimit(char separatorCharacter)](#delimit-char-) | ब्रैकेट के बिना सेपरेटर वर्ण के साथ चाइल्ड तत्वों को सीमांकित करता है। |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य वर्णों में फ्रेमिंग के रूप में संलग्न करता है। |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य में फ्रेमिंग के रूप में संलग्न करता है और सेपरेटर वर्ण के साथ सीमांकित करता है। |
| [toMathArray()](#toMathArray--) | चाइल्ड तत्वों को एक लंबवत सरणी में रखता है। |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | इस [MathBlock](../../com.aspose.slides/mathblock) की सामग्री को MathML के रूप में सहेजता है। |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

MathBlock क्लास का नया उदाहरण आरंभ करता है।

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

एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व को इसमें रखता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | ब्लॉक में रखने के लिए गणितीय तत्व। |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | ब्लॉक में रखने के लिए गणितीय तत्व। |

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में वास्तविक रूप से उपस्थित चाइल्ड गणित तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**वापसी:**  
int  
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर IMathElement को प्राप्त या सेट करता है।

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
| index | int | आइटम का शून्य-आधारित अनुक्रमांक |

**वापसी:**  
[IMathElement](../../com.aspose.slides/imathelement) - गणितीय तत्व।  
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

निर्दिष्ट अनुक्रमांक पर IMathElement को प्राप्त या सेट करता है।

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
| index | int | आइटम का शून्य-आधारित अनुक्रमांक |
| value | [IMathElement](../../com.aspose.slides/imathelement) | गणितीय तत्व। |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

false लौटाता है क्योंकि चाइल्ड तत्वों का संग्रह संशोधित किया जा सकता है।

**वापसी:**  
boolean  
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

चाइल्ड तत्व प्राप्त करें

**वापसी:**  
com.aspose.slides.IMathElement[]  
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**वापसी:**  
com.aspose.slides.IDOMObject  
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

संग्रह के अंत में एक गणितीय तत्व जोड़ता है।

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह के अंत में जोड़ने के लिए IMathElement। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्वों को हटाता है।

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

निर्धारित करता है कि क्या संग्रह में एक विशिष्ट मान मौजूद है।

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह में खोजने के लिए वस्तु। |

**वापसी:**  
boolean - true यदि वस्तु संग्रह में पायी गई; अन्यथा false।  
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

निर्दिष्ट सरणी में कॉपी करता है।

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
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | कॉपी करने के लिए सरणी। |
| arrayIndex | int | कॉपी शुरू करने का अनुक्रमांक। |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

संग्रह से विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह से हटाने वाली वस्तु। |

**वापसी:**  
boolean - true यदि वस्तु सफलतापूर्वक हटाई गई; अन्यथा false। यह मेथड तब भी false लौटाता है जब वस्तु मूल संग्रह में नहीं पायी गई।  
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एनेमरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - संग्रह को इटररेट करने के लिए उपयोग किया जाने वाला IGenericEnumerator।  
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

संपूर्ण संग्रह के लिए जावा इटरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.IEnumerator - पूरे संग्रह के लिए java.util.Iterator।  
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

संग्रह में विशिष्ट गणितीय तत्व का अनुक्रमांक निर्धारित करता है।

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | संग्रह में खोजने वाला तत्व। |

**वापसी:**  
int - यदि तत्व संग्रह में पाया जाता है तो उसका अनुक्रमांक; अन्यथा -1।  
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में MathElement डालता है।

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
| index | int | MathElement को डालने के लिए शून्य-आधारित अनुक्रमांक। |
| item | [IMathElement](../../com.aspose.slides/imathelement) | डालने के लिए MathElement। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट अनुक्रमांक पर संग्रह से तत्व को हटाता है।

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
| index | int | हटाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | जोड़ने वाला तत्व। |

**वापसी:**  
[IMathBlock](../../com.aspose.slides/imathblock) - वर्तमान IMathBlock का उदाहरण।  
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
| mathText | java.lang.String | जोड़ने वाला गणितीय पाठ। |

**वापसी:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस उदाहरण और निर्दिष्ट तर्क को सम्मिलित करने वाला नया IMathBlock।  
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

एक अन्य गणितीय ब्लॉक को इस ब्लॉक के साथ जोड़ता है।

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

**वापसी:**  
[IMathBlock](../../com.aspose.slides/imathblock) - जोड़ने के बाद यह गणितीय ब्लॉक।  
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

सेपरेटर वर्ण (कोष्ठकों के बिना) के साथ चाइल्ड तत्वों को सीमांकित करता है।

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char | सेपरेटर वर्ण। |

**वापसी:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व।  
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य में फ्रेमिंग के रूप में संलग्न करता है।

--------------------

> ```
> उदाहरण:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारंभिक वर्ण (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | समाप्ति वर्ण (आमतौर पर दायाँ कोष्ठक) |

**वापसी:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें निर्दिष्ट वर्ण फ्रेमिंग के रूप में शामिल हैं।  
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य में फ्रेमिंग के रूप में संलग्न करता है और सेपरेटर वर्ण के साथ सीमांकित करता है।

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारंभिक वर्ण (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | समाप्ति वर्ण (आमतौर पर दायाँ कोष्ठक) |
| separatorCharacter | char | सेपरेटर वर्ण। |

**वापसी:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें निर्दिष्ट वर्ण फ्रेमिंग और डिलिमिटर के रूप में शामिल हैं।  
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

चाइल्ड तत्वों को एक लंबवत सरणी में रखता है।

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**वापसी:**  
[IMathArray](../../com.aspose.slides/imatharray) - प्रकार [IMathArray](../../com.aspose.slides/imatharray) का नया उदाहरण।  
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

इस [MathBlock](../../com.aspose.slides/mathblock) की सामग्री को MathML के रूप में सहेजता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |