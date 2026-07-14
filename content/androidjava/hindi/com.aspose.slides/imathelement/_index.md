---
title: IMathElement
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: किसी भी गणितीय तत्व का बेस इंटरफ़ेस: भिन्न, गणितीय पाठ, फ़ंक्शन, कई तत्वों के साथ अभिव्यक्ति आदि
type: docs
url: /hi/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

किसी भी गणितीय तत्व का बेस इंटरफ़ेस: भिन्न, गणितीय पाठ, फ़ंक्शन, कई तत्वों के साथ अभिव्यक्ति आदि

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [join(String mathText)](#join-java.lang.String-) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [divide(String denominator)](#divide-java.lang.String-) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [enclose()](#enclose--) | गणितीय तत्व को कोष्ठकों में घेरता है |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | इस तत्व को निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य वर्णों में फ्रेमिंग के रूप में घेरता है |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क की फ़ंक्शन लेता है |
| [function(String functionArgument)](#function-java.lang.String-) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क की फ़ंक्शन लेता है |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त तर्क के साथ लेता है |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त तर्क के साथ लेता है |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | सबस्क्रिप्ट बनाता है |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | सबस्क्रिप्ट बनाता है |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | सुपरस्क्रिप्ट बनाता है |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | निर्दिष्ट तर्क से दिए गए क्रमांक का गणितीय मूल निर्दिष्ट करता है |
| [radical(String degree)](#radical-java.lang.String-) | निर्दिष्ट तर्क से दिए गए क्रमांक का गणितीय मूल निर्दिष्ट करता है |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | ऊपरी सीमा लेता है |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | ऊपरी सीमा लेता है |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | निचली सीमा लेता है |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | निचली सीमा लेता है |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | एक N-ary ऑपरेटर बनाता है |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | एक N-ary ऑपरेटर बनाता है |
| [toMathArray()](#toMathArray--) | एक लंबवत सरणी में रखता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | समाकल लेता है |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | समाकल लेता है |
| [integral(int integralType)](#integral-int-) | बिना सीमाओं के समाकल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | समाकल लेता है |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | समाकल लेता है |
| [accent(char accentCharacter)](#accent-char-) | एक उच्चारण चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [overbar()](#overbar--) | इस तत्व के ऊपर एक रेखा सेट करता है |
| [underbar()](#underbar--) | इस तत्व के नीचे एक रेखा सेट करता है |
| [group()](#group--) | निचले घुंघराले ब्रेस का उपयोग करके इस तत्व को एक समूह में रखता है |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | समूहित वर्ण जैसे निचला घुंघराला ब्रेस या अन्य का उपयोग करके इस तत्व को एक समूह में रखता है |
| [toBorderBox()](#toBorderBox--) | इस तत्व को एक सीमा बॉक्स में रखता है |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | इस तत्व को एक सीमा बॉक्स में रखता है |
| [toBox()](#toBox--) | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या गणितीय पाठ के अन्य भागों को समूहित करने के लिए किया जाता है |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

संतान तत्व प्राप्त करें

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | जोड़ने के लिए तत्व |

**रिटर्न:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस इंस्टेंस और निर्दिष्ट तर्क को शामिल करने वाला नया IMathBlock
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | जोड़ने के लिए गणितीय पाठ |

**रिटर्न:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस इंस्टेंस और निर्दिष्ट तर्क को शामिल करने वाला नया IMathBlock
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | हर |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| denominator | java.lang.String | हर |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | हर |
| fractionType | int | भिन्न प्रकार: Bar, NoBar, Skewed, Linear |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| denominator | java.lang.String | हर |
| fractionType | int | भिन्न प्रकार: Bar, NoBar, Skewed, Linear |

**रिटर्न:**  
[IMathFraction](../../com.aspose.slides/imathfraction) - नया भिन्न
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

गणितीय तत्व को कोष्ठकों में घेरता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें कोष्ठक शामिल हैं
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

इस तत्व को निर्दिष्ट वर्णों जैसे कोष्ठक या अन्य वर्णों में फ्रेमिंग के रूप में घेरता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारम्भिक वर्ण (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | समाप्ति वर्ण (आमतौर पर दायाँ कोष्ठक) |

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय तत्व जिसमें निर्दिष्ट वर्ण फ्रेमिंग के रूप में शामिल हैं
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क की फ़ंक्शन लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन का तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क की फ़ंक्शन लेता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionArgument | java.lang.String | फ़ंक्शन का तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन नाम |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionName | java.lang.String | फ़ंक्शन नाम |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | int | एक तर्क वाले सामान्य फ़ंक्शन प्रकारों में से एक |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त तर्क के साथ लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' का आधार '5' के लिए लॉगरिद्म लौटाता है
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | int | दो तर्क वाले सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन प्रकार के अनुसार अतिरिक्त तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और अतिरिक्त तर्क के साथ लेता है

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' का आधार '5' के लिए लॉगरिद्म लौटाता है
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | int | दो तर्क वाले सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | फ़ंक्शन प्रकार के अनुसार अतिरिक्त तर्क |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - प्रकार [IMathFunction](../../com.aspose.slides/imathfunction) का नया गणितीय तत्व
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबस्क्रिप्ट (दाएँ तरफ निचला सूचकांक) |

**रिटर्न:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - प्रकार [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) का नया गणितीय तत्व
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | java.lang.String | सबस्क्रिप्ट (दाएँ तरफ निचला सूचकांक) |

**रिटर्न:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - प्रकार [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) का नया गणितीय तत्व
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरस्क्रिप्ट (दाएँ तरफ ऊपरी सूचकांक) |

**रिटर्न:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - प्रकार [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) का नया गणितीय तत्व
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| superscript | java.lang.String | सुपरस्क्रिप्ट (दाएँ तरफ ऊपरी सूचकांक) |

**रिटर्न:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - प्रकार [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) का नया गणितीय तत्व
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबस्क्रिप्ट (दाएँ तरफ निचला सूचकांक) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरस्क्रिप्ट (दाएँ तरफ ऊपरी सूचकांक) |

**रिटर्न:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - प्रकार [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) का नया गणितीय तत्व
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | java.lang.String | सबस्क्रिप्ट (दाएँ तरफ निचला सूचकांक) |
| superscript | java.lang.String | सुपरस्क्रिप्ट (दाएँ तरफ ऊपरी सूचकांक) |

**रिटर्न:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - प्रकार [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) का नया गणितीय तत्व
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | सबस्क्रिप्ट (बाएँ तरफ निचला सूचकांक) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | सुपरस्क्रिप्ट (बाएँ तरफ ऊपरी सूचकांक) |

**रिटर्न:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - प्रकार [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) का नया गणितीय तत्व
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | java.lang.String | सबस्क्रिप्ट (बाएँ तरफ निचला सूचकांक) |
| superscript | java.lang.String | सुपरस्क्रिप्ट (बाएँ तरफ ऊपरी सूचकांक) |

**रिटर्न:**  
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - प्रकार [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) का नया गणितीय तत्व
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

निर्दिष्ट तर्क से दिए गए क्रमांक का गणितीय मूल निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | मूल तर्क |

**रिटर्न:**  
[IMathRadical](../../com.aspose.slides/imathradical) - प्रकार [IMathRadical](../../com.aspose.slides/imathradical) का नया इंस्टेंस
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

निर्दिष्ट तर्क से दिए गए क्रमांक का गणितीय मूल निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| degree | java.lang.String | मूल तर्क |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा |

**रिटर्न:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - प्रकार [IMathLimit](../../com.aspose.slides/imathlimit) का नया इंस्टेंस
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

ऊपरी सीमा लेता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| limit | java.lang.String | सीमा |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| limit | java.lang.String | सीमा |

**रिटर्न:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - प्रकार [IMathLimit](../../com.aspose.slides/imathlimit) का नया इंस्टेंस
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

एक N-ary ऑपरेटर बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | int | N-ary ऑपरेटर प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

**रिटर्न:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

एक N-ary ऑपरेटर बनाता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | int | N-ary ऑपरेटर प्रकार |
| lowerLimit | java.lang.String | निचली सीमा |
| upperLimit | java.lang.String | ऊपरी सीमा |

**रिटर्न:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

एक लंबवत सरणी में रखता है

--------------------

> ```
> Example:
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की ऊपरी सीमा |
| limitLocations | int | सीमाओं का स्थान |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | समाकल की ऊपरी सीमा |

**रिटर्न:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

बिना सीमाओं के समाकल लेता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | java.lang.String | समाकल की निचली सीमा |
| upperLimit | java.lang.String | समाकल की ऊपरी सीमा |
| limitLocations | int | सीमाओं का स्थान |

**रिटर्न:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

समाकल लेता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| integralType | int | समाकल प्रकार |
| lowerLimit | java.lang.String | समाकल की निचली सीमा |
| upperLimit | java.lang.String | समाकल की ऊपरी सीमा |

**रिटर्न:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - प्रकार [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) का नया इंस्टेंस
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

एक उच्चारण चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| accentCharacter | char | उच्चारण अक्षर। मान (U+0300-U+036F) या (U+20D0-U+20EF) रेंज में होना चाहिए |

**रिटर्न:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - प्रकार [IMathAccent](../../com.aspose.slides/imathaccent) का नया इंस्टेंस
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

इस तत्व के ऊपर एक रेखा सेट करता है

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**रिटर्न:**  
[IMathBar](../../com.aspose.slides/imathbar) - प्रकार [IMathBar](../../com.aspose.slides/imathbar) का नया इंस्टेंस
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

इस तत्व के नीचे एक रेखा सेट करता है

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**रिटर्न:**  
[IMathBar](../../com.aspose.slides/imathbar) - प्रकार [IMathBar](../../com.aspose.slides/imathbar) का नया इंस्टेंस
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

निचले घुंघराले ब्रेस का उपयोग करके इस तत्व को एक समूह में रखता है

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

समुहत वर्ण जैसे निचला घुंघराला ब्रेस या अन्य का उपयोग करके इस तत्व को एक समूह में रखता है

--------------------

> ```
> उदाहरण:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| character | char | समूहित वर्ण जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई भी अन्य |
| position | int | समूहित वर्ण की स्थिति |
| verticalJustification | int | समूहित वर्ण का लंबवत समायोजन। यह वस्तु को बेसलाइन के सापेक्ष कैसे संरेखित करता है, निर्दिष्ट करता है। उदाहरण के लिए, जब समूहित वर्ण वस्तु के ऊपर हो, तो Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है; जब Bottom सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर होता है |

**रिटर्न:**  
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - प्रकार [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) का नया इंस्टेंस
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

इस तत्व को एक सीमा बॉक्स में रखता है

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**रिटर्न:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - इस तत्व के अंदर रखा गया सीमा बॉक्स
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

इस तत्व को एक सीमा बॉक्स में रखता है

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| hideTop | boolean | शीर्ष किनारा छुपाएँ |
| hideBottom | boolean | निचला किनारा छुपाएँ |
| hideLeft | boolean | बायाँ किनारा छुपाएँ |
| hideRight | boolean | दायाँ किनारा छुपाएँ |
| strikethroughHorizontal | boolean | सीमा बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | सीमा बॉक्स लंबवत स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | निचले बाएँ से ऊपर दाएँ तक स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | ऊपर बाएँ से निचले दाएँ तक स्ट्राइकथ्रू |

**रिटर्न:**  
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - इस तत्व के अंदर रखा गया सीमा बॉक्स
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या गणितीय पाठ के अन्य भागों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में काम कर सकता है, संरेखण बिंदु के साथ या बिना, लाइन-ब्रेक बिंदु के रूप में, या इस तरह समूहित किया जा सकता है कि लाइन-ब्रेक की अनुमति न हो।

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**रिटर्न:**  
[IMathBox](../../com.aspose.slides/imathbox) - इस तत्व के अंदर रखा गया तार्किक बॉक्स