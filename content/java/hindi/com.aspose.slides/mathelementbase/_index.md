---
title: MathElementBase
second_title: Aspose.Slides for Java API संदर्भ
description: IMathElement के लिए बेस क्लास, जिसमें सभी विरासत में मिलने वाले वर्गों में सामान्य कुछ विधियों का कार्यान्वयन शामिल है। केवल आंतरिक उपयोग के लिए।
type: docs
url: /hi/com.aspose.slides/mathelementbase/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject  
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

IMathElement के लिए बेस क्लास है जिसमें कुछ विधियों का कार्यान्वयन शामिल है जो सभी व्युत्पन्न वर्गों में सामान्य हैं। केवल आंतरिक उपयोग के लिए। व्युत्पन्न वर्ग को IMathElement होना चाहिए।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate वस्तु को लौटाता है। |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [join(String mathText)](#join-java.lang.String-) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | यह अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [divide(String denominator)](#divide-java.lang.String-) | यह अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है |
| [enclose()](#enclose--) | गणितीय तत्व को कोष्ठक में घेरता है |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में घेरता है |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में इस्तेमाल करके एक आर्ग्युमेंट का फ़ंक्शन लेता है |
| [function(String functionArgument)](#function-java.lang.String-) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में इस्तेमाल करके एक आर्ग्युमेंट का फ़ंक्शन लेता है |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त आर्ग्युमेंट |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त आर्ग्युमेंट |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | सबस्क्रिप्ट बनाता है |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | सबस्क्रिप्ट बनाता है |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | सुपरस्क्रिप्ट बनाता है |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | बाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | निर्दिष्ट आर्ग्युमेंट से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [radical(String degree)](#radical-java.lang.String-) | निर्दिष्ट आर्ग्युमेंट से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | ऊपरी सीमा लेता है |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | ऊपरी सीमा लेता है |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | निचली सीमा लेता है |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | निचली सीमा लेता है |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | एक एन-एरी ऑपरेटर बनाता है |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | एक एन-एरी ऑपरेटर बनाता है |
| [toMathArray()](#toMathArray--) | एक ऊर्ध्वाधर सरणी डालता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | समाकल लेता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | समाकल लेता है |
| [integral(int integralType)](#integral-int-) | सीमा के बिना समाकल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | समाकल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | समाकल लेता है |
| [accent(char accentCharacter)](#accent-char-) | एक उच्चारण चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [overbar()](#overbar--) | इस तत्व के ऊपर एक बार सेट करता है |
| [underbar()](#underbar--) | इस तत्व के नीचे एक बार सेट करता है |
| [group()](#group--) | नीचे कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | नीचे कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [toBorderBox()](#toBorderBox--) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [toBox()](#toBox--) | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। |
| [getChildren()](#getChildren--) | बच्चा तत्व प्राप्त करें |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate वस्तु को लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**  
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है

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
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | जोड़ने के लिए तत्व |

**रिटर्न:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस इंस्टेंस और निर्दिष्ट आर्ग्युमेंट को शामिल करने वाला नया IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है

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
| mathText | java.lang.String | जोड़ने के लिए गणितीय पाठ |

**रिटर्न:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस इंस्टेंस और निर्दिष्ट आर्ग्युमेंट को शामिल करने वाला नया IMathBlock

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

यह अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | हर |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

यह अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | java.lang.String | हर |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | हर |
| fractionType | int | भिन्न प्रकार: Bar, NoBar, Skewed, Linear |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | java.lang.String | हर |
| fractionType | int | भिन्न प्रकार: Bar, NoBar, Skewed, Linear |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

गणितीय तत्व को कोष्ठक में घेरता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें कोष्ठक शामिल है

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में घेरता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारम्भिक अक्षर (आमतौर पर बायाँ ब्रेस) |
| endingCharacter | char | समाप्ति अक्षर (आमतौर पर दायाँ ब्रेस) |

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें निर्दिष्ट अक्षर फ्रेमिंग रूप में हैं

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

इस इंस्टेंस को फ़ंक्शन नाम के रूप में इस्तेमाल करके एक आर्ग्युमेंट का फ़ंक्शन लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन का आर्ग्युमेंट |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

इस इंस्टेंस को फ़ंक्शन नाम के रूप में इस्तेमाल करके एक आर्ग्युमेंट का फ़ंक्शन लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionArgument | java.lang.String | फ़ंक्शन का आर्ग्युमेंट |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन नाम |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | java.lang.String | फ़ंक्शन नाम |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | एक-आर्ग्युमेंट सामान्य फ़ंक्शन प्रकारों में से एक |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त आर्ग्युमेंट

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' का आधार '5' के लिए लघुगणक लौटाता है
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | दो-आर्ग्युमेंट सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन प्रकार के अनुसार अतिरिक्त आर्ग्युमेंट |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त आर्ग्युमेंट

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' का आधार '5' के लिए लघुगणक लौटाता है
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | दो-आर्ग्युमेंट सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | फ़ंक्शन प्रकार के अनुसार अतिरिक्त आर्ग्युमेंट |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

सबस्क्रिप्ट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबस्क्रिप्ट (दाईं ओर निचला इंडेक्स) |

**रिटर्न:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - प्रकार [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) का नया गणितीय तत्व

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

सबस्क्रिप्ट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | java.lang.String | सबस्क्रिप्ट (दाईं ओर निचला इंडेक्स) |

**रिटर्न:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - प्रकार [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) का नया गणितीय तत्व

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरस्क्रिप्ट (दाईं ओर ऊपरी इंडेक्स) |

**रिटर्न:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - प्रकार [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) का नया गणितीय तत्व

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| superscript | java.lang.String | सुपरस्क्रिप्ट (दाईं ओर ऊपरी इंडेक्स) |

**रिटर्न:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - प्रकार [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) का नया गणितीय तत्व

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबस्क्रिप्ट (दाईं ओर निचला इंडेक्स) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरस्क्रिप्ट (दाईं ओर ऊपरी इंडेक्स) |

**रिटर्न:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - प्रकार [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) का नया गणितीय तत्व

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

दाईं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है
> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | सबस्क्रिप्ट (दाएँ का निचला इंडेक्स) |
| superscript | java.lang.String | सुपरस्क्रिप्ट (दाएँ का ऊपरी इंडेक्स) |

**रिटर्न:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - नया गणित तत्व प्रकार [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबस्क्रिप्ट (बाएँ का निचला इंडेक्स) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरस्क्रिप्ट (बाएँ का ऊपरी इंडेक्स) |

**रिटर्न:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - नया गणित तत्व प्रकार [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | सबस्क्रिप्ट (बाएँ का निचला इंडेक्स) |
| superscript | java.lang.String | सुपरस्क्रिप्ट (बाएँ का ऊपरी इंडेक्स) |

**रिटर्न:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - नया गणित तत्व प्रकार [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

निर्दिष्ट तर्क से दिए गये डिग्री की गणितीय मूल (रूट) निर्धारित करता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | रेडिकल का तर्क |

**रिटर्न:**
[IMathRadical](../../com.aspose.slides/imathradical) - नया प्रकार का उदाहरण [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

निर्दिष्ट तर्क से दिए गये डिग्री की गणितीय मूल (रूट) निर्धारित करता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | रेडिकल का तर्क |

**रिटर्न:**
[IMathRadical](../../com.aspose.slides/imathradical) - नया प्रकार का उदाहरण [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

ऊपरी सीमा लेता है

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया प्रकार का उदाहरण [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

ऊपरी सीमा लेता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | सीमा |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया प्रकार का उदाहरण [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

निचली सीमा लेता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया प्रकार का उदाहरण [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

निचली सीमा लेता है

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | सीमा |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया प्रकार का उदाहरण [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

एक N-ary ऑपरेटर बनाता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | N-ary ऑपरेटर प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया प्रकार का उदाहरण [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

एक N-ary ऑपरेटर बनाता है

---

> ```
> उदाहरण:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | N-ary ऑपरेटर प्रकार |
| lowerLimit | java.lang.String | निचली सीमा |
| upperLimit | java.lang.String | ऊपरी सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया प्रकार का उदाहरण [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

एक लम्बवत एरे में रखता है

---

> ```
> उदाहरण:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**रिटर्न:**
[IMathArray](../../com.aspose.slides/imatharray) - नया प्रकार का उदाहरण [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

समाकल लेता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की ऊपरी सीमा |
| limitLocations | int | सीमाओं का स्थान |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया प्रकार का उदाहरण [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

समाकल लेता है

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की ऊपरी सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया प्रकार का उदाहरण [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

सीमाओं के बिना समाकल लेता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया प्रकार का उदाहरण [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

समाकल लेता है

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | java.lang.String | समाकल की निचली सीमा |
| upperLimit | java.lang.String | समाकल की ऊपरी सीमा |
| limitLocations | int | सीमाओं का स्थान |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया प्रकार का उदाहरण [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

समाकल लेता है

---

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | java.lang.String | समाकल की निचली सीमा |
| upperLimit | java.lang.String | समाकल की ऊपरी सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया प्रकार का उदाहरण [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

इस तत्व के ऊपर एक आवाज़ चिह्न सेट करता है (ऊपर का अक्षर)

---

> ```
> उदाहरण:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | आवाज़ अक्षर। मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा में होना चाहिए |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - नया प्रकार का उदाहरण [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

इस तत्व के ऊपर एक बार सेट करता है

---

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**रिटर्न:**
[IMathBar](../../com.aspose.slides/imathbar) - नया प्रकार का उदाहरण [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

इस तत्व के नीचे एक बार सेट करता है

---

> ```
> उदाहरण:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**रिटर्न:**
[IMathBar](../../com.aspose.slides/imathbar) - नया प्रकार का उदाहरण [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

एक निचले कर्ली ब्रैकेट का उपयोग कर इस तत्व को समूह में रखता है

---

> ```
> उदाहरण:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```


**रिटर्न:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - नया प्रकार का उदाहरण [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

नीचे कर्ली ब्रैकेट या अन्य किसी समूह अक्षर का उपयोग कर इस तत्व को समूह में रखता है

---

> ```
> उदाहरण:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | समूह अक्षर，例如 BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | int | समूह अक्षर की स्थिति |
| verticalJustification | int | समूह अक्षर का ऊर्ध्वाधर समायोजन। वस्तु को बेसलाइन के सापेक्ष संरेखित करता है। उदाहरण के लिये, जब समूह अक्षर वस्तु के ऊपर हो, तो Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है; जब Bottom सेट किया जाता है, तो वस्तु का निचला हिस्सा बेसलाइन पर स्थित होता है |

**रिटर्न:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - नया प्रकार का उदाहरण [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

इस तत्व को एक बॉर्डर-बॉक्स में रखता है

---

> ```
> उदाहरण:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**रिटर्न:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - बॉर्डर-बॉक्स जिसमें यह तत्व स्थित है
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

इस तत्व को एक बॉर्डर-बॉक्स में रखता है

---

> ```
> उदाहरण:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | शीर्ष किनारा छिपाएँ |
| hideBottom | boolean | निचला किनारा छिपाएँ |
| hideLeft | boolean | बायाँ किनारा छिपाएँ |
| hideRight | boolean | दायाँ किनारा छिपाएँ |
| strikethroughHorizontal | boolean | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | बॉर्डर बॉक्स लंबवत स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | बॉर्डर बॉक्स नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | बॉर्डर बॉक्स ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू |

**रिटर्न:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - बॉर्डर-बॉक्स जिसमें यह तत्व स्थित है
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिये किया जाता है। एक बॉक्स्ड वस्तु (उदाहरण के लिये) ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकती है, चाहे संरेखण बिंदु हो या न हो, लाइन-ब्रेक बिंदु के रूप में उपयोग की जा सकती है, या इस तरह समूहित हो कि लाइन-ब्रेक की अनुमति न हो।

---

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**रिटर्न:**
[IMathBox](../../com.aspose.slides/imathbox) - इस तत्व को अंदर रखे हुए तार्किक बॉक्स
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

संतान (चाइल्ड) तत्व प्राप्त करता है

**रिटर्न:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) की एरे