---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: एनिमेशन बिंदु को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipoint/
---```
public interface IPoint
```

एनिमेशन बिंदु को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTime()](#getTime--) | समय मान को दर्शाता है। |
| [setTime(float value)](#setTime-float-) | समय मान को दर्शाता है। |
| [getValue()](#getValue--) | बिंदु मान को दर्शाता है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | बिंदु मान को दर्शाता है। |
| [getFormula()](#getFormula--) | फ़ॉर्मूले मूल्य, from, to, by विशेषताओं के भीतर इनसे बने हो सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' गुणधर्म संदर्भ (होस्ट समर्थित गुणधर्म) उदाहरण के लिए: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" पढ़ें/लिखें स्ट्रिंग। |
| [setFormula(String value)](#setFormula-java.lang.String-) | फ़ॉर्मूले मूल्य, from, to, by विशेषताओं के भीतर इनसे बने हो सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' गुणधर्म संदर्भ (होस्ट समर्थित गुणधर्म) उदाहरण के लिए: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" पढ़ें/लिखें स्ट्रिंग। |
### getTime() {#getTime--}
```
public abstract float getTime()
```


समय मान को दर्शाता है। पढ़ें/लिखें float.

**Returns:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```


समय मान को दर्शाता है। पढ़ें/लिखें float.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


बिंदु मान को दर्शाता है। केवल: bool, ColorFormat, float, int, string। पढ़ें/लिखें ऑब्जेक्ट।

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


बिंदु मान को दर्शाता है। केवल: bool, ColorFormat, float, int, string। पढ़ें/लिखें ऑब्जेक्ट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


फ़ॉर्मूले मूल्य, from, to, by विशेषताओं के भीतर इनसे बने हो सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' गुणधर्म संदर्भ (होस्ट समर्थित गुणधर्म) उदाहरण के लिए: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" पढ़ें/लिखें स्ट्रिंग।

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


फ़ॉर्मूले मूल्य, from, to, by विशेषताओं के भीतर इनसे बने हो सकते हैं: मानक अंकगणितीय ऑपरेटर्स: '+', '-', '*', '/', '^', '%' (mod) स्थिरांक: 'pi' 'e' शर्तीय ऑपरेटर्स: 'abs', 'min', 'max', '?' (if) तुलना ऑपरेटर्स: '==', '>=', '', '!=', '!' त्रिकोणमितीय ऑपरेटर्स: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' प्राकृतिक लघुगणक 'ln()' गुणधर्म संदर्भ (होस्ट समर्थित गुणधर्म) उदाहरण के लिए: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" पढ़ें/लिखें स्ट्रिंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |