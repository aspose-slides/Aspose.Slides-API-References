---
title: Point
second_title: Aspose.Slides for Android, Java API रेफ़रेंस के द्वारा
description: एनीमेशन पॉइंट को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/point/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)  
```
public class Point implements IPoint
```

एनीमेशन पॉइंट को दर्शाता है।

## कन्स्ट्रक्टर

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Point()](#Point--) | डिफ़ॉल्ट कन्स्ट्रक्टर। |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | समय, मान और सूत्र के साथ एनीमेशन पॉइंट बनाएं। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTime()](#getTime--) | समय मान को दर्शाता है। |
| [setTime(float value)](#setTime-float-) | समय मान को दर्शाता है। |
| [getValue()](#getValue--) | पॉइंट मान को दर्शाता है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | पॉइंट मान को दर्शाता है। |
| [getFormula()](#getFormula--) | मानों के भीतर, from, to, by गुणों में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ने/लिखने योग्य स्ट्रिंग। |
| [setFormula(String value)](#setFormula-java.lang.String-) | मानों के भीतर, from, to, by गुणों में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ने/लिखने योग्य स्ट्रिंग। |

### Point() {#Point--}
```
public Point()
```

डिफ़ॉल्ट कन्स्ट्रक्टर।

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

समय, मान और सूत्र के साथ एनीमेशन पॉइंट बनाएं।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| time | float | समय मान। |
| value | java.lang.Object | पॉइंट मान। |
| formula | java.lang.String | सूत्र। |

### getTime() {#getTime--}
```
public final float getTime()
```

समय मान को दर्शाता है। पढ़ने/लिखने योग्य फ्लोट।

**रिटर्न वैल्यू:**
float

### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

समय मान को दर्शाता है। पढ़ने/लिखने योग्य फ्लोट।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

पॉइंट मान को दर्शाता है। केवल: bool, ColorFormat, float, int, string। पढ़ने/लिखने योग्य ऑब्जेक्ट।

**रिटर्न वैल्यू:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

पॉइंट मान को दर्शाता है। केवल: bool, ColorFormat, float, int, string। पढ़ने/लिखने योग्य ऑब्जेक्ट।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

मानों के भीतर, from, to, by गुणों में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ने/लिखने योग्य स्ट्रिंग।

**रिटर्न वैल्यू:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

मानों के भीतर, from, to, by गुणों में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ने/लिखने योग्य स्ट्रिंग।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |