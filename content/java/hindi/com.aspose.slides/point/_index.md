---
title: Point
second_title: Aspose.Slides for Java API संदर्भ
description: एनीमेशन बिंदु का प्रतिनिधित्व करता है।
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

एनीमेशन बिंदु का प्रतिनिधित्व करता है।
## निर्माणकर्ता

| निर्माता | विवरण |
| --- | --- |
| [Point()](#Point--) | डिफ़ॉल्ट निर्माणकर्ता। |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | समय, मान और फ़ॉर्मूला के साथ एनीमेशन बिंदु बनाएं। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTime()](#getTime--) | समय मान का प्रतिनिधित्व करता है। |
| [setTime(float value)](#setTime-float-) | समय मान का प्रतिनिधित्व करता है। |
| [getValue()](#getValue--) | बिंदु मान का प्रतिनिधित्व करता है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | बिंदु मान का प्रतिनिधित्व करता है। |
| [getFormula()](#getFormula--) | मूल्यों, from, to, by विशेषताओं के भीतर सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी संदर्भ (होस्ट समर्थित प्रॉपर्टी) उदाहरण: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | मूल्यों, from, to, by विशेषताओं के भीतर सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी संदर्भ (होस्ट समर्थित प्रॉपर्टी) उदाहरण: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String. |
### Point() {#Point--}
```
public Point()
```


डिफ़ॉल्ट निर्माणकर्ता।

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


समय, मान और फ़ॉर्मूला के साथ एनीमेशन बिंदु बनाएं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| time | float | समय मान। |
| value | java.lang.Object | बिंदु मान। |
| formula | java.lang.String | फ़ॉर्मूला। |

### getTime() {#getTime--}
```
public final float getTime()
```


समय मान का प्रतिनिधित्व करता है। Read/write float.

**वापसी:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


समय मान का प्रतिनिधित्व करता है। Read/write float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


बिंदु मान का प्रतिनिधित्व करता है। Only: bool, ColorFormat, float, int, string. Read/write Object.

**वापसी:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


बिंदु मान का प्रतिनिधित्व करता है। Only: bool, ColorFormat, float, int, string. Read/write Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


मूल्यों, from, to, by विशेषताओं के भीतर सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी संदर्भ (होस्ट समर्थित प्रॉपर्टी) उदाहरण: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**वापसी:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


मूल्यों, from, to, by विशेषताओं के भीतर सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी संदर्भ (होस्ट समर्थित प्रॉपर्टी) उदाहरण: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |