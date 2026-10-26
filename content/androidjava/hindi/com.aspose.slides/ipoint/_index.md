---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Represent animation point.
type: docs
url: /hi/com.aspose.slides/ipoint/
---```
public interface IPoint
```

एनीमेशन बिंदु का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getTime()](#getTime--) | समय मान को दर्शाता है। |
| [setTime(float value)](#setTime-float-) | समय मान को दर्शाता है। |
| [getValue()](#getValue--) | बिंदु मान को दर्शाता है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | बिंदु मान को दर्शाता है। |
| [getFormula()](#getFormula--) | मानों के भीतर, from, to, by विशेषताओं में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज़) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ें/लिखें String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | मानों के भीतर, from, to, by विशेषताओं में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज़) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ें/लिखें String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

समय मान को दर्शाता है। पढ़ें/लिखें float.

**रिटर्न:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

समय मान को दर्शाता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

बिंदु मान को दर्शाता है। केवल: bool, ColorFormat, float, int, string. पढ़ें/लिखें Object.

**रिटर्न:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

बिंदु मान को दर्शाता है। केवल: bool, ColorFormat, float, int, string. पढ़ें/लिखें Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

मानों के भीतर, from, to, by विशेषताओं में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज़) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

मानों के भीतर, from, to, by विशेषताओं में सूत्र इनका उपयोग करके बनाए जा सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' प्रॉपर्टी रेफ़रेंसेज़ (होस्ट समर्थित प्रॉपर्टीज़) उदाहरण के लिए: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |