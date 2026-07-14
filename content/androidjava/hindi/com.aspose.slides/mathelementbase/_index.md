---
title: MathElementBase
second_title: Android के लिये Aspose.Slides, Java API रेफ़रेंस के माध्यम से
description: IMathElement के लिए बेस क्लास, जिसमें उन कुछ मेथड्स का कार्यान्वयन है जो सभी विरासती क्लासों में सामान्य हैं। केवल आंतरिक उपयोग के लिए।
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

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.

## Methods

| मेथड | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate ऑब्जेक्ट लौटाता है। |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [join(String mathText)](#join-java.lang.String-) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है |
| [divide(String denominator)](#divide-java.lang.String-) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | निर्दिष्ट प्रकार का एक भिन्न इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | निर्दिष्ट प्रकार का एक भिन्न इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [enclose()](#enclose--) | गणितीय तत्व को कोष्ठक में घेरता है |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में घेरता है |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [function(String functionArgument)](#function-java.lang.String-) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क निर्दिष्ट करता है |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क निर्दिष्ट करता है |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | सबस्क्रिप्ट बनाता है |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | सबस्क्रिप्ट बनाता है |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | सुपरस्क्रिप्ट बनाता है |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [radical(String degree)](#radical-java.lang.String-) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | ऊपरी सीमा लेता है |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | ऊपरी सीमा लेता है |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | निचली सीमा लेता है |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | निचली सीमा लेता है |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | एक N-ary ऑपरेटर बनाता है |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | एक N-ary ऑपरेटर बनाता है |
| [toMathArray()](#toMathArray--) | एक वर्टिकल एरे में रखता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | इंटेग्रल लेता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | इंटेग्रल लेता है |
| [integral(int integralType)](#integral-int-) | सीमा के बिना इंटेग्रल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | इंटेग्रल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | इंटेग्रल लेता है |
| [accent(char accentCharacter)](#accent-char-) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [overbar()](#overbar--) | इस तत्व के ऊपर एक बार सेट करता है |
| [underbar()](#underbar--) | इस तत्व के नीचे एक बार सेट करता है |
| [group()](#group--) | एक नीचे के कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | एक समूहित अक्षर (जैसे नीचे का कर्ली ब्रैकेट या अन्य) का उपयोग करके इस तत्व को समूह में रखता है |
| [toBorderBox()](#toBorderBox--) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [toBox()](#toBox--) | इस तत्व को एक नॉन-विज़ुअल बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न्स:**  
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

**रिटर्न्स:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस इंस्टेंस और निर्दिष्ट तर्क को शामिल करने वाला नया IMathBlock

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

**रिटर्न्स:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस इंस्टेंस और निर्दिष्ट तर्क को शामिल करने वाला नया IMathBlock

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | डिनॉमिनेटर |

**रिटर्न्स:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | java.lang.String | डिनॉमिनेटर |

**रिटर्न्स:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

निर्दिष्ट प्रकार का एक भिन्न इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | डिनॉमिनेटर |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**रिटर्न्स:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

निर्दिष्ट प्रकार का एक भिन्न इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | java.lang.String | डिनॉमिनेटर |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**रिटर्न्स:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

गणितीय तत्व को कोष्ठक में घेरता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**रिटर्न्स:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) प्रकार का गणितीय तत्व जिसमें कोष्ठक शामिल है

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में घेरता है

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
| beginningCharacter | char | प्रारंभिक अक्षर (आमतौर पर बायाँ ब्रैकेट) |
| endingCharacter | char | समाप्ति अक्षर (आमतौर पर दायाँ ब्रैकेट) |

**रिटर्न्स:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) प्रकार का गणितीय तत्व जिसमें निर्दिष्ट अक्षर फ्रेमिंग के रूप में शामिल हैं

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन का तर्क |

**रिटर्न्स:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) प्रकार का नया गणितीय तत्व

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके किसी तर्क का फ़ंक्शन लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionArgument | java.lang.String | फ़ंक्शन का तर्क |

**रिटर्न्स:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) प्रकार का नया गणितीय तत्व

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन नाम |

**रिटर्न्स:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) प्रकार का नया गणितीय तत्व

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | java.lang.String | फ़ंक्शन नाम |

**रिटर्न्स:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) प्रकार का नया गणितीय तत्व

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

एक तर्क वाले सामान्य फ़ंक्शन प्रकार में से किसी एक को उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | एक तर्क वाले सामान्य फ़ंक्शन प्रकार में से कोई एक |

**रिटर्न्स:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) प्रकार का नया गणितीय तत्व

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' का बेस '5' के लिए लघुगणक लौटाता है
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | दो तर्क वाले सामान्य फ़ंक्शन प्रकार में से कोई एक: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

**रिटर्न्स:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) प्रकार का नया गणितीय तत्व

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' का बेस '5' के लिए लघुगणक लौटाता है
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | दो तर्क वाले सामान्य फ़ंक्शन प्रकार में से कोई एक: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

**रिटर्न्स:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) प्रकार का नया गणितीय तत्व

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | दाएँ ओर नीचे वाला सूचक (सबस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) प्रकार का नया गणितीय तत्व

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
| subscript | java.lang.String | दाएँ ओर नीचे वाला सूचक (सबस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) प्रकार का नया गणितीय तत्व

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | दाएँ ओर ऊपर वाला सूचक (सुपरस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) प्रकार का नया गणितीय तत्व

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
| superscript | java.lang.String | दाएँ ओर ऊपर वाला सूचक (सुपरस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) प्रकार का नया गणितीय तत्व

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> उदाहरण
```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | दाएँ ओर नीचे वाला सूचक (सबस्क्रिप्ट) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | दाएँ ओर ऊपर वाला सूचक (सुपरस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) प्रकार का नया गणितीय तत्व

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | java.lang.String | दाएँ ओर नीचे वाला सूचक (सबस्क्रिप्ट) |
| superscript | java.lang.String | दाएँ ओर ऊपर वाला सूचक (सुपरस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) प्रकार का नया गणितीय तत्व

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | बाएँ ओर नीचे वाला सूचक (सबस्क्रिप्ट) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | बाएँ ओर ऊपर वाला सूचक (सुपरस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) प्रकार का नया गणितीय तत्व

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | java.lang.String | बाएँ ओर नीचे वाला सूचक (सबस्क्रिप्ट) |
| superscript | java.lang.String | बाएँ ओर ऊपर वाला सूचक (सुपरस्क्रिप्ट) |

**रिटर्न्स:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) प्रकार का नया गणितीय तत्व

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है।

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | रेडिकल का तर्क |

**रिटर्न्स:**  
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical) प्रकार का नया इंस्टेंस

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| degree | java.lang.String | रेडिकल का तर्क |

**रिटर्न्स:**  
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical) प्रकार का नया इंस्टेंस

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

ऊपरी सीमा लेता है

--------------------

> ```
> उदाहरण
```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा |

**रिटर्न्स:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) प्रकार का नया इंस्टेंस

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

ऊपरी सीमा लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | java.lang.String | सीमा |

**रिटर्न्स:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) प्रकार का नया इंस्टेंस

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

निचली सीमा लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा |

**रिटर्न्स:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) प्रकार का नया इंस्टेंस

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

निचली सीमा लेता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | java.lang.String | सीमा |

**रिटर्न्स:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) प्रकार का नया इंस्टेंस

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

एक N-ary ऑपरेटर बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | N-ary ऑपरेटर का प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

**रिटर्न्स:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) प्रकार का नया इंस्टेंस

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

एक N-ary ऑपरेटर बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | N-ary ऑपरेटर का प्रकार |
| lowerLimit | java.lang.String | निचली सीमा |
| upperLimit | java.lang.String | ऊपरी सीमा |

**रिटर्न्स:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) प्रकार का नया इंस्टेंस

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

एक वर्टिकल एरे में रखता है

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**रिटर्न्स:**  
[IMathArray](../../com.aspose.slides/imatharray) - [IMathArray](../../com.aspose.slides/imatharray) प्रकार का नया इंस्टेंस

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

इंटेग्रल लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | int | इंटेग्रल प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | इंटेग्रल की निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | इंटेग्रल की ऊपरी सीमा |
| limitLocations | int | सीमाओं का स्थान |

**रिटर्न्स:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) प्रकार का नया इंस्टेंस

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

इंटेग्रल लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | int | इंटेग्रल प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | इंटेग्रल की निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | इंटेग्रल की ऊपरी सीमा |

**रिटर्न्स:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) प्रकार का नया इंस्टेंस

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

सीमा के बिना इंटेग्रल लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | int | इंटेग्रल प्रकार |

**रिटर्न्स:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) प्रकार का नया इंस्टेंस

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

इंटेग्रल लेता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | int | इंटेग्रल प्रकार |
| lowerLimit | java.lang.String | इंटेग्रल की निचली सीमा |
| upperLimit | java.lang.String | इंटेग्रल की ऊपरी सीमा |
| limitLocations | int | सीमाओं का स्थान |

**रिटर्न्स:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) प्रकार का नया इंस्टेंस

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

इंटेग्रल लेता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | int | इंटेग्रल प्रकार |
| lowerLimit | java.lang.String | इंटेग्रल की निचली सीमा |
| upperLimit | java.lang.String | इंटेग्रल की ऊपरी सीमा |

**रिटर्न्स:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) प्रकार का नया इंस्टेंस

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

इस तत्व के ऊपर एक अक्षर (एक्सेंट) सेट करता है

--------------------

> ```
> उदाहरण:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| accentCharacter | char | एक्सेंट अक्षर। मान (U+0300-U+036F) या (U+20D0-U+20EF) रेंज में होना चाहिए |

**रिटर्न्स:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - [IMathAccent](../../com.aspose.slides/imathaccent) प्रकार का नया इंस्टेंस

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

इस तत्व के ऊपर एक बार सेट करता है

--------------------

> ```
> उदाहरण:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**रिटर्न्स:**  
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar) प्रकार का नया इंस्टेंस

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

इस तत्व के नीचे एक बार सेट करता है

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**रिटर्न्स:**  
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar) प्रकार का नया इंस्टेंस

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

एक नीचे के कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**रिटर्न्स:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) प्रकार का नया इंस्टेंस

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

एक समूहित अक्षर (जैसे नीचे का कर्ली ब्रैकेट या अन्य) का उपयोग करके इस तत्व को समूह में रखता है

--------------------

> ```
> उदाहरण:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| character | char | समूहित अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | int | समूहित अक्षर की स्थिति |
| verticalJustification | int | समूहित अक्षर की वर्टिकल जस्टिफ़िकेशन। वस्तु को बेसलाइन के सापेक्ष संरेखित करता है। उदाहरण के लिए, जब समूहित अक्षर वस्तु के ऊपर हो, तो Top का अर्थ है कि वस्तु का शीर्ष बेसलाइन पर रहेगा; जब Bottom सेट किया जाता है, तो वस्तु का निचला हिस्सा बेसलाइन पर रहेगा |

**रिटर्न्स:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) प्रकार का नया इंस्टेंस

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

एक बॉर्डर-बॉक्स में इस तत्व को रखता है

--------------------

> ```
> उदाहरण:
```

**रिटर्न्स:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - इस तत्व को अंदर रखे हुए बॉर्डर-बॉक्स

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

एक बॉर्डर-बॉक्स में इस तत्व को रखता है

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hideTop | boolean | शीर्ष किनारा छुपाएँ |
| hideBottom | boolean | निचला किनारा छुपाएँ |
| hideLeft | boolean | बायाँ किनारा छुपाएँ |
| hideRight | boolean | दायाँ किनारा छुपाएँ |
| strikethroughHorizontal | boolean | बॉर्डर बॉक्स में क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | बॉर्डर बॉक्स में लंबवत स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | नीचे-बाएँ से ऊपर-दाएँ तक स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | ऊपर-बाएँ से नीचे-दाएँ तक स्ट्राइकथ्रू |

**रिटर्न्स:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - इस तत्व को अंदर रखे हुए बॉर्डर-बॉक्स

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

एक नॉन-विज़ुअल बॉक्स (तार्किक समूह) में इस तत्व को रखता है, जिसका उपयोग समीकरण या गणितीय पाठ के अन्य उदाहरणों के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट को (उदाहरण के लिए) ऑपरेटर एमुलेटर के रूप में उपयोग किया जा सकता है, जिसमें संरेखण बिंदु हो या नहीं, लाइन-ब्रेक बिंदु के रूप में काम कर सकता है, या समूहित किया जा सकता है ताकि लाइन-ब्रेक की अनुमति न हो।

--------------------

> ```
> उदाहरण:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**रिटर्न्स:**  
[IMathBox](../../com.aspose.slides/imathbox) - इस तत्व को अंदर रखे हुए लॉजिकल बॉक्स

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

संतान तत्व प्राप्त करें

**रिटर्न्स:**  
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) की array