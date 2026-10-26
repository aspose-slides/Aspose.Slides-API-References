---
title: Trendline
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: क्लास चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करती है
type: docs
url: /hi/com.aspose.slides/trendline/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)  
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

क्लास चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करता है

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। |
| [getTrendlineType()](#getTrendlineType--) | ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। |
| [setTrendlineType(int value)](#setTrendlineType-int-) | ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। |
| [getFormat()](#getFormat--) | ट्रेंड लाइन का स्वरूप प्रस्तुत करता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | ट्रेंड लाइन का स्वरूप प्रस्तुत करता है। |
| [getBackward()](#getBackward--) | ट्रेंड लाइन डेटा से पहले विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। |
| [setBackward(double value)](#setBackward-double-) | ट्रेंड लाइन डेटा से पहले विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। |
| [getForward()](#getForward--) | ट्रेंडलाइन डेटा के बाद विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। |
| [setForward(double value)](#setForward-double-) | ट्रेंडलाइन डेटा के बाद विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। |
| [getIntercept()](#getIntercept--) | ट्रेंडलाइन के y-अक्ष को पार करने के मान को निर्दिष्ट करता है। |
| [setIntercept(double value)](#setIntercept-double-) | ट्रेंडलाइन के y-अक्ष को पार करने के मान को निर्दिष्ट करता है। |
| [getDisplayEquation()](#getDisplayEquation--) | निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर प्रदर्शित हो (Rsquaredvalue के समान लेबल में)। |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर प्रदर्शित हो (Rsquaredvalue के समान लेबल में)। |
| [getOrder()](#getOrder--) | बहुपद ट्रेंड लाइन का क्रम निर्दिष्ट करता है। |
| [setOrder(byte value)](#setOrder-byte-) | बहुपद ट्रेंड लाइन का क्रम निर्दिष्ट करता है। |
| [getPeriod()](#getPeriod--) | चल औसत ट्रेंड लाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। |
| [setPeriod(byte value)](#setPeriod-byte-) | चल औसत ट्रेंड लाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | निर्दिष्ट करता है कि ट्रेंडलाइन का R-वर्ग मान चार्ट पर प्रदर्शित हो (समीकरण के समान लेबल में)। |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | निर्दिष्ट करता है कि ट्रेंडलाइन का R-वर्ग मान चार्ट पर प्रदर्शित हो (समीकरण के समान लेबल में)। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ट्रेंडलाइन से संबंधित लेजेंड एंट्री को प्रस्तुत करता है, केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)। |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | पैरामीटर "text" में दिए गए पाठ से TextFrameForOverriding को प्रारम्भित करता है। |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | समृद्ध स्वरूपित पाठ शामिल कर सकता है। |
| [getTextFormat()](#getTextFormat--) | पाठ स्वरूप लौटाता है। |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TrendlineType](../../com.aspose.slides/trendlinetype).

**रिटर्न:**  
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TrendlineType](../../com.aspose.slides/trendlinetype).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

ट्रेंड लाइन का स्वरूप प्रस्तुत करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

ट्रेंड लाइन का स्वरूप प्रस्तुत करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

ट्रेंड लाइन डेटा से पहले विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**रिटर्न:**  
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

ट्रेंड लाइन डेटा से पहले विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

ट्रेंडलाइन डेटा के बाद विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**रिटर्न:**  
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

ट्रेंडलाइन डेटा के बाद विस्तारित होने वाली श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

ट्रेंडलाइन के y-अक्ष को पार करने के मान को निर्दिष्ट करता है। यह प्रॉपर्टी केवल exp, linear या poly प्रकार की ट्रेंडलाइन के लिए समर्थित है। पढ़ें/लिखें double.

**रिटर्न:**  
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

ट्रेंडलाइन के y-अक्ष को पार करने के मान को निर्दिष्ट करता है। यह प्रॉपर्टी केवल exp, linear या poly प्रकार की ट्रेंडलाइन के लिए समर्थित है। पढ़ें/लिखें double.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर प्रदर्शित हो (Rsquaredvalue के समान लेबल में)। पढ़ें/लिखें boolean.

**रिटर्न:**  
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर प्रदर्शित हो (Rsquaredvalue के समान लेबल में)। पढ़ें/लिखें boolean.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

बहुपद ट्रेंड लाइन का क्रम निर्दिष्ट करता है। अन्य ट्रेंड लाइन प्रकारों के लिए यह अनदेखा किया जाता है। मान 2 से 6 के बीच होना चाहिए। पढ़ें/लिखें byte.

**रिटर्न:**  
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

बहुपद ट्रेंड लाइन का क्रम निर्दिष्ट करता है। अन्य ट्रेंड लाइन प्रकारों के लिए यह अनदेखा किया जाता है। मान 2 से 6 के बीच होना चाहिए। पढ़ें/लिखें byte.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

चल औसत ट्रेंडलाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। अन्य ट्रेंड लाइन वैरिएंट के लिए यह अनदेखा किया जाता है। मान 2 से 255 के बीच होना चाहिए। पढ़ें/लिखें byte.

**रिटर्न:**  
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

चल औसत ट्रेंडलाइन के लिए ट्रेंड लाइन की अवधि निर्दिष्ट करता है। अन्य ट्रेंड लाइन वैरिएंट के लिए यह अनदेखा किया जाता है। मान 2 से 255 के बीच होना चाहिए। पढ़ें/लिखें byte.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

निर्दिष्ट करता है कि ट्रेंडलाइन का R-वर्ग मान चार्ट पर प्रदर्शित हो (समीकरण के समान लेबल में)। पढ़ें/लिखें boolean.

**रिटर्न:**  
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

निर्दिष्ट करता है कि ट्रेंडलाइन का R-वर्ग मान चार्ट पर प्रदर्शित हो (समीकरण के समान लेबल में)। पढ़ें/लिखें boolean.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ट्रेंडलाइन से संबंधित लेजेंड एंट्री को प्रस्तुत करता है, केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**रिटर्न:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

पैरामीटर "text" में दिए गए पाठ से TextFrameForOverriding को प्रारम्भित करता है। यदि TextFrameForOverriding पहले से प्रारम्भित है तो केवल उसका पाठ बदलता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | नया TextFrameForOverriding हेतु पाठ। |

**रिटर्न:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

समृद्ध स्वरूपित पाठ शामिल कर सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह स्वरूपित पाठ डेटा लेबल के स्वतः-जनरेटेड पाठ को ओवरराइड करता है। स्वतः-जनरेटेड डेटा लेबल पाठ वह पाठ है जिसका प्रबंधन ShowSeriesName, ShowValue आदि प्रॉपर्टी करता है और TextFormatManager.TextFormat प्रॉपर्टी द्वारा स्वरूपित होता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe).

**रिटर्न:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

पाठ स्वरूप लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**रिटर्न:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart).

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide).

**रिटर्न:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**रिटर्न:**  
[IPresentation](../../com.aspose.slides/ipresentation)