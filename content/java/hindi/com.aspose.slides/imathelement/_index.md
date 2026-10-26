---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: किसी भी गणितीय तत्व जैसे अंश, गणितीय पाठ, फ़ंक्शन, बहु-तत्वीय अभिव्यक्ति आदि का मूल इंटरफ़ेस
type: docs
url: /hi/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

किसी भी गणितीय तत्व का मूल इंटरफ़ेस: अंश, गणितीय पाठ, फ़ंक्शन, कई तत्वों वाली अभिव्यक्ति आदि

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करता है |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [join(String mathText)](#join-java.lang.String-) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | इस अंशांक और निर्दिष्ट हर के साथ एक अंश बनाता है |
| [divide(String denominator)](#divide-java.lang.String-) | इस अंशांक और निर्दिष्ट हर के साथ एक अंश बनाता है |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | निर्दिष्ट प्रकार के अंश को इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | निर्दिष्ट प्रकार के अंश को इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [enclose()](#enclose--) | गणितीय तत्व को कोष्ठकों में बंद करता है |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | इस तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में बंद करता है |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [function(String functionArgument)](#function-java.lang.String-) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन और अतिरिक्त तर्क लेता है |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन और अतिरिक्त तर्क लेता है |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | सबसक्रिप्ट बनाता है |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | सबसक्रिप्ट बनाता है |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | सुपरसक्रिप्ट बनाता है |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | सुपरसक्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | दाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | दाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | बाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | बाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [radical(String degree)](#radical-java.lang.String-) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्धारित करता है। |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | ऊपरी सीमा लेता है |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | ऊपरी सीमा लेता है |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | निचली सीमा लेता है |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | निचली सीमा लेता है |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N-ary ऑपरेटर बनाता है |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N-ary ऑपरेटर बनाता है |
| [toMathArray()](#toMathArray--) | ऊर्ध्वाधर सरणी में रखता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | समाकल लेता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | समाकल लेता है |
| [integral(int integralType)](#integral-int-) | सीमा के बिना समाकल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | समाकल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | समाकल लेता है |
| [accent(char accentCharacter)](#accent-char-) | एक उच्चारण चिन्ह सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [overbar()](#overbar--) | इस तत्व के ऊपर एक बार सेट करता है |
| [underbar()](#underbar--) | इस तत्व के नीचे एक बार सेट करता है |
| [group()](#group--) | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | नीचे की कर्ली ब्रैकेट या अन्य समूह वर्ण का उपयोग करके इस तत्व को समूह में रखता है |
| [toBorderBox()](#toBorderBox--) | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [toBox()](#toBox--) | समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग होने वाले गैर-दृश्य बॉक्स (तार्किक समूह) में इस तत्व को रखता है |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

संतान तत्व प्राप्त करता है

**रिटर्न:**  
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
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
[IMathBlock](../../com.aspose.slides/imathblock) - एक नया IMathBlock जिसमें यह इंस्टेंस और निर्दिष्ट तर्क शामिल है

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
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
[IMathBlock](../../com.aspose.slides/imathblock) - एक नया IMathBlock जिसमें यह इंस्टेंस और निर्दिष्ट तर्क शामिल है

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

इस अंशांक और निर्दिष्ट हर के साथ एक अंश बनाता है

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
[IMathFraction](../../com.aspose.slides/imathfraction) - नया अंश

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

इस अंशांक और निर्दिष्ट हर के साथ एक अंश बनाता है

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
[IMathFraction](../../com.aspose.slides/imathfraction) - नया अंश

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

निर्दिष्ट प्रकार के अंश को इस अंशांक और निर्दिष्ट हर के साथ बनाता है

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
| fractionType | int | अंश प्रकार: Bar, NoBar, Skewed, Linear |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया अंश

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

निर्दिष्ट प्रकार के अंश को इस अंशांक और निर्दिष्ट हर के साथ बनाता है

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
| fractionType | int | अंश प्रकार: Bar, NoBar, Skewed, Linear |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया अंश

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

गणितीय तत्व को कोष्ठकों में बंद करता है

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
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

इस तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षर फ्रेमिंग के रूप में बंद करता है

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
| beginningCharacter | char | प्रारंभिक अक्षर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | समाप्ति अक्षर (आमतौर पर दायाँ कोष्ठक) |

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें निर्दिष्ट अक्षर फ्रेमिंग के रूप में शामिल हैं

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है

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
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन का तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है

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
| functionArgument | java.lang.String | फ़ंक्शन का तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

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
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

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
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | एक-तर्क वाले सामान्य फ़ंक्शन प्रकार में से एक |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन और अतिरिक्त तर्क लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' की लॉगरिद्म को बेस '5' पर लौटाता है
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | दो-तर्क वाले सामान्य फ़ंक्शन प्रकार में से एक: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन प्रकार के अनुसार अतिरिक्त तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन और अतिरिक्त तर्क लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' की लॉगरिद्म को बेस '5' पर लौटाता है
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | int | दो-तर्क वाले सामान्य फ़ंक्शन प्रकार में से एक: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | फ़ंक्शन प्रकार के अनुसार अतिरिक्त तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

सबसक्रिप्ट बनाता है

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबसक्रिप्ट (दाएँ नीचे निचला सूचक) |

**रिटर्न:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - प्रकार [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) का नया गणितीय तत्व

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

सबसक्रिप्ट बनाता है

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
| subscript | java.lang.String | सबसक्रिप्ट (दाएँ नीचे निचला सूचक) |

**रिटर्न:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - प्रकार [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) का नया गणितीय तत्व

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

सुपरसक्रिप्ट बनाता है

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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरसक्रिप्ट (दाएँ ऊपर ऊपरी सूचक) |

**रिटर्न:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - प्रकार [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) का नया गणितीय तत्व

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

सुपरसक्रिप्ट बनाता है

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
| superscript | java.lang.String | सुपरसक्रिप्ट (दाएँ ऊपर ऊपरी सूचक) |

**रिटर्न:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - प्रकार [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) का नया गणितीय तत्व

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

दाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबसक्रिप्ट (दाएँ नीचे निचला सूचक) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरसक्रिप्ट (दाएँ ऊपर ऊपरी सूचक) |

**रिटर्न:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - प्रकार [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) का नया गणितीय तत्व

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
Creates subscript and superscript on the right
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
| subscript | java.lang.String | Subscript (lower index on the right) → सबस्क्रिप्ट (दाएँ तरफ का निचला सूचक) |
| superscript | java.lang.String | Superscript (upper index on the right) → सुपरस्क्रिप्ट (दाएँ तरफ का ऊपरी सूचक) |

**रिटर्न:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - प्रकार [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) का नया गणित तत्व

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creates subscript and superscript on the left
--------------------
> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) → सबस्क्रिप्ट (बाएँ तरफ का निचला सूचक) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) → सुपरस्क्रिप्ट (बाएँ तरफ का ऊपरी सूचक) |

**रिटर्न:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - प्रकार [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) का नया गणित तत्व

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Creates subscript and superscript on the left
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
| subscript | java.lang.String | Subscript (lower index on the left) → सबस्क्रिप्ट (बाएँ तरफ का निचला सूचक) |
| superscript | java.lang.String | Superscript (upper index on the left) → सुपरस्क्रिप्ट (बाएँ तरफ का ऊपरी सूचक) |

**रिटर्न:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - प्रकार [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) का नया गणित तत्व

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्धारित करता है।
--------------------
> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical → रैडिकल का तर्क |

**रिटर्न:**
[IMathRadical](../../com.aspose.slides/imathradical) - प्रकार [IMathRadical](../../com.aspose.slides/imathradical) का नया इंस्टेंस

### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्धारित करता है।
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
| degree | java.lang.String | Argument of Radical → रैडिकल का तर्क |

**रिटर्न:**
[IMathRadical](../../com.aspose.slides/imathradical) - प्रकार [IMathRadical](../../com.aspose.slides/imathradical) का नया इंस्टेंस

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

ऊपरी सीमा लेता है
--------------------
> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - प्रकार [IMathLimit](../../com.aspose.slides/imathlimit) का नया इंस्टेंस

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
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
| limit | java.lang.String | limit |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - प्रकार [IMathLimit](../../com.aspose.slides/imathlimit) का नया इंस्टेंस

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

निचली सीमा लेता है
--------------------
> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - प्रकार [IMathLimit](../../com.aspose.slides/imathlimit) का नया इंस्टेंस

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
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
| limit | java.lang.String | limit |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - प्रकार [IMathLimit](../../com.aspose.slides/imathlimit) का नया इंस्टेंस

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
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
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
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
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस

### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

एक लंबवत सरणी में रखता है
--------------------
> ```
> उदाहरण:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**रिटर्न:**
[IMathArray](../../com.aspose.slides/imatharray) - प्रकार [IMathArray](../../com.aspose.slides/imatharray) का नया इंस्टेंस

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

समाकल लेता है
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
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

समाकल लेता है
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
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस

### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

सीमाओं के बिना समाकल लेता है
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
| integralType | int | Integral type |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

समाकल लेता है
--------------------
> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

समाकल लेता है
--------------------
> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस

### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

एक लहजा चिह्न सेट करता है (इस तत्व के ऊपर का अक्षर)
--------------------
> ```
> उदाहरण:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - प्रकार [IMathAccent](../../com.aspose.slides/imathaccent) का नया इंस्टेंस

### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

इस तत्व के ऊपर एक बार सेट करता है
--------------------
> ```
> उदाहरण:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**रिटर्न:**
[IMathBar](../../com.aspose.slides/imathbar) - प्रकार [IMathBar](../../com.aspose.slides/imathbar) का नया इंस्टेंस

### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

इस तत्व के नीचे एक बार सेट करता है
--------------------
> ```
> उदाहरण:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**रिटर्न:**
[IMathBar](../../com.aspose.slides/imathbar) - प्रकार [IMathBar](../../com.aspose.slides/imathbar) का नया इंस्टेंस

### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है
--------------------
> ```
> उदाहरण:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```


**रिटर्न:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - प्रकार [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) का नया इंस्टेंस

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

कर्ली ब्रैकेट या किसी अन्य समूह वर्ण का उपयोग करके इस तत्व को समूह में रखता है
--------------------
> ```
> उदाहरण:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other → समूह वर्ण जैसे नीचे की कर्ली ब्रैकेट (U+23DF) या कोई अन्य |
| position | int | Position of grouping character → समूह वर्ण की स्थिति |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline → समूह वर्ण का लम्बर उन्मुखीकरण। वस्तु की बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह वर्ण वस्तु के ऊपर हो, तो Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर आता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का नीचे बेसलाइन पर होता है। |

**रिटर्न:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - प्रकार [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) का नया इंस्टेंस

### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

इस तत्व को बॉर्डर-बॉक्स में रखता है
--------------------
> ```
> उदाहरण:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**रिटर्न:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - इस तत्व के साथ अंदर रखे हुए बॉर्डर-बॉक्स

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

इस तत्व को बॉर्डर-बॉक्स में रखता है
--------------------
> ```
> उदाहरण:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**रिटर्न:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - इस तत्व के साथ अंदर रखे हुए बॉर्डर-बॉक्स

### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जो समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना एक ऑपरेटर इम्युलेटर के रूप में कार्य कर सकता है, लाइन-ब्रेक बिंदु के रूप में उपयोग हो सकता है, या इस तरह समूहित हो सकता है कि लाइन-ब्रेक की अनुमति न हो।

--------------------
> ```
> उदाहरण:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**रिटर्न:**
[IMathBox](../../com.aspose.slides/imathbox) - इस तत्व के साथ अंदर रखे हुए तार्किक बॉक्स