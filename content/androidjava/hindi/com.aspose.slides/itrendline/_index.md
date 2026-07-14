---
title: ITrendline
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: क्लास चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/itrendline/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

क्लास चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। |
| [getTrendlineType()](#getTrendlineType--) | ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। |
| [setTrendlineType(int value)](#setTrendlineType-int-) | ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। |
| [getFormat()](#getFormat--) | ट्रेंड लाइन का फ़ॉर्मेट दर्शाता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | ट्रेंड लाइन का फ़ॉर्मेट दर्शाता है। |
| [getBackward()](#getBackward--) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जिससे ट्रेंड लाइन डेटा से पहले विस्तारित होती है जिसे श्रृंखला के लिए ट्रेंड किया जा रहा है। |
| [setBackward(double value)](#setBackward-double-) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जिससे ट्रेंड लाइन डेटा से पहले विस्तारित होती है जिसे श्रृंखला के लिए ट्रेंड किया जा रहा है। |
| [getForward()](#getForward--) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जिससे ट्रेंडलाइन डेटा के बाद विस्तारित होती है जिसे श्रृंखला के लिए ट्रेंड किया जा रहा है। |
| [setForward(double value)](#setForward-double-) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जिससे ट्रेंडलाइन डेटा के बाद विस्तारित होती है जिसे श्रृंखला के लिए ट्रेंड किया जा रहा है। |
| [getIntercept()](#getIntercept--) | ट्रेंडलाइन द्वारा y-अक्ष को पार करने वाले मान को निर्दिष्ट करता है। |
| [setIntercept(double value)](#setIntercept-double-) | ट्रेंडलाइन द्वारा y-अक्ष को पार करने वाले मान को निर्दिष्ट करता है। |
| [getDisplayEquation()](#getDisplayEquation--) | निर्दिष्ट करता है कि ट्रेंडलाइन के समीकरण को चार्ट पर (Rsquaredvalue के समान लेबल में) प्रदर्शित किया जाए। |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | निर्दिष्ट करता है कि ट्रेंडलाइन के समीकरण को चार्ट पर (Rsquaredvalue के समान लेबल में) प्रदर्शित किया जाए। |
| [getOrder()](#getOrder--) | पॉलिनोमियल ट्रेंड लाइन का क्रम निर्दिष्ट करता है। |
| [setOrder(byte value)](#setOrder-byte-) | पॉलिनोमियल ट्रेंड लाइन का क्रम निर्दिष्ट करता है। |
| [getPeriod()](#getPeriod--) | मूविंग एवरेज ट्रेंड लाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। |
| [setPeriod(byte value)](#setPeriod-byte-) | मूविंग एवरेज ट्रेंड लाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | निर्दिष्ट करता है कि ट्रेंडलाइन का R-स्क्वेर्ड मान चार्ट पर (समीकरण के समान लेबल में) प्रदर्शित हो। |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | निर्दिष्ट करता है कि ट्रेंडलाइन का R-स्क्वेर्ड मान चार्ट पर (समीकरण के समान लेबल में) प्रदर्शित हो। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस ट्रेंडलाइन से संबंधित लेजेंड एंट्री दर्शाता है केवल पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**वापसी:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ट्रेंड लाइन का फ़ॉर्मेट दर्शाता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat).

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

ट्रेंड लाइन का फ़ॉर्मेट दर्शाता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

स्कैटर या गैर-स्कैटर चार्ट पर, ट्रेंड लाइन डेटा से पहले विस्तारित होने वाली श्रेणियों (या इकाइयों) की संख्या निर्दिष्ट करता है। मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**वापसी:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

स्कैटर या गैर-स्कैटर चार्ट पर, ट्रेंड लाइन डेटा से पहले विस्तारित होने वाली श्रेणियों (या इकाइयों) की संख्या निर्दिष्ट करता है। मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

स्कैटर या गैर-स्कैटर चार्ट पर, ट्रेंडलाइन डेटा के बाद विस्तारित होने वाली श्रेणियों (या इकाइयों) की संख्या निर्दिष्ट करता है। मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**वापसी:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

स्कैटर या गैर-स्कैटर चार्ट पर, ट्रेंडलाइन डेटा के बाद विस्तारित होने वाली श्रेणियों (या इकाइयों) की संख्या निर्दिष्ट करता है। मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

ट्रेंडलाइन द्वारा y-अक्ष को पार करने वाले मान को निर्दिष्ट करता है। यह प्रॉपर्टी केवल तब समर्थित है जब ट्रेंडलाइन प्रकार exp, linear, या poly हो। पढ़ें/लिखें double.

**वापसी:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

ट्रेंडलाइन द्वारा y-अक्ष को पार करने वाले मान को निर्दिष्ट करता है। यह प्रॉपर्टी केवल तब समर्थित है जब ट्रेंडलाइन प्रकार exp, linear, या poly हो। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर (Rsquaredvalue के समान लेबल में) प्रदर्शित किया जाए। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर (Rsquaredvalue के समान लेबल में) प्रदर्शित किया जाए। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

पॉलिनोमीयल ट्रेंड लाइन का क्रम निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन प्रकारों के लिए अनदेखा किया जाता है। मान 2 से 6 के बीच होना चाहिए। पढ़ें/लिखें byte.

**वापसी:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

पॉलिनोमीयल ट्रेंड लाइन का क्रम निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन प्रकारों के लिए अनदेखा किया जाता है। मान 2 से 6 के बीच होना चाहिए। पढ़ें/लिखें byte.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

मूविंग एवरेज ट्रेंड लाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन वैरिएंट के लिए अनदेखा किया जाता है। मान 2 से 255 के बीच होना चाहिए। पढ़ें/लिखें byte.

**वापसी:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

मूविंग एवरेज ट्रेंड लाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। यह अन्य ट्रेंड लाइन वैरिएंट के लिए अनदेखा किया जाता है। मान 2 से 255 के बीच होना चाहिए। पढ़ें/लिखें byte.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

निर्दिष्ट करता है कि ट्रेंडलाइन का R-स्क्वेर्ड मान चार्ट पर (समीकरण के समान लेबल में) प्रदर्शित हो। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

निर्दिष्ट करता है कि ट्रेंडलाइन का R-स्क्वेर्ड मान चार्ट पर (समीकरण के समान लेबल में) प्रदर्शित हो। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

इस ट्रेंडलाइन से संबंधित लेजेंड एंट्री दर्शाता है केवल पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**वापसी:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)