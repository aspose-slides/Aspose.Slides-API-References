---
title: Trendline
second_title: Aspose.Slides for Java API संदर्भ
description: क्लास चार्ट श्रृंखला की प्रवृत्ति रेखा का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/trendline/
---
**उत्तराधिकार:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

क्लास चार्ट श्रृंखला की प्रवृत्ति रेखा का प्रतिनिधित्व करता है
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | प्रवृत्ति रेखा का नाम प्राप्त करता है या सेट करता है। |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | प्रवृत्ति रेखा का नाम प्राप्त करता है या सेट करता है। |
| [getTrendlineType()](#getTrendlineType--) | प्रवृत्ति रेखा का प्रकार प्राप्त करता है या सेट करता है। |
| [setTrendlineType(int value)](#setTrendlineType-int-) | प्रवृत्ति रेखा का प्रकार प्राप्त करता है या सेट करता है। |
| [getFormat()](#getFormat--) | प्रवृत्ति रेखा का प्रारूप प्रतिनिधित्व करता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | प्रवृत्ति रेखा का प्रारूप प्रतिनिधित्व करता है। |
| [getBackward()](#getBackward--) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा से पहले विस्तारित होती है। |
| [setBackward(double value)](#setBackward-double-) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा से पहले विस्तारित होती है। |
| [getForward()](#getForward--) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा के बाद विस्तारित होती है। |
| [setForward(double value)](#setForward-double-) | श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा के बाद विस्तारित होती है। |
| [getIntercept()](#getIntercept--) | वह मान निर्दिष्ट करता है जहाँ प्रवृत्ति रेखा y-अक्ष को काटती है। |
| [setIntercept(double value)](#setIntercept-double-) | वह मान निर्दिष्ट करता है जहाँ प्रवृत्ति रेखा y-अक्ष को काटती है। |
| [getDisplayEquation()](#getDisplayEquation--) | यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का समीकरण चार्ट पर (Rsquaredvalue के समान लेबल में) दिखाया जाए। |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का समीकरण चार्ट पर (Rsquaredvalue के समान लेबल में) दिखाया जाए। |
| [getOrder()](#getOrder--) | बहुपद प्रवृत्ति रेखा का क्रम निर्दिष्ट करता है। |
| [setOrder(byte value)](#setOrder-byte-) | बहुपद प्रवृत्ति रेखा का क्रम निर्दिष्ट करता है। |
| [getPeriod()](#getPeriod--) | चालू औसत प्रवृत्ति रेखा के लिए अवधि निर्दिष्ट करता है। |
| [setPeriod(byte value)](#setPeriod-byte-) | चालू औसत प्रवृत्ति रेखा के लिए अवधि निर्दिष्ट करता है। |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का R-स्क्वेयर मान चार्ट पर (समीकरण के समान लेबल में) दिखाया जाए। |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का R-स्क्वेयर मान चार्ट पर (समीकरण के समान लेबल में) दिखाया जाए। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस प्रवृत्ति रेखा से संबंधित लेजेंड एंट्री। केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)। |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | टेक्स्ट पैरामीटर "text" के साथ TextFrameForOverriding को आरम्भ करता है। |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | समृद्ध स्वरूपित टेक्स्ट रख सकता है। |
| [getTextFormat()](#getTextFormat--) | टेक्स्ट स्वरूप लौटाता है। |
| [getChart()](#getChart--) | मूल चार्ट लौटाता है। |
| [getSlide()](#getSlide--) | FillFormat की मूल स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की मूल प्रेजेंटेशन लौटाता है। |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

प्रवृत्ति रेखा का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

प्रवृत्ति रेखा का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

प्रवृत्ति रेखा का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TrendlineType](../../com.aspose.slides/trendlinetype).

**रिटर्न:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

प्रवृत्ति रेखा का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TrendlineType](../../com.aspose.slides/trendlinetype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

प्रवृत्ति रेखा का प्रारूप प्रतिनिधित्व करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

प्रवृत्ति रेखा का प्रारूप प्रतिनिधित्व करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा से पहले विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा से पहले विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा के बाद विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

श्रेणियों (या स्कैटर चार्ट पर इकाइयों) की संख्या निर्दिष्ट करता है जो प्रवृत्ति रेखा डेटा के बाद विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

वह मान निर्दिष्ट करता है जहाँ प्रवृत्ति रेखा y-अक्ष को काटती है। यह प्रॉपर्टी केवल तब समर्थित है जब प्रवृत्ति रेखा प्रकार exp, linear, या poly हो। पढ़ें/लिखें double.

**रिटर्न:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

वह मान निर्दिष्ट करता है जहाँ प्रवृत्ति रेखा y-अक्ष को काटती है। यह प्रॉपर्टी केवल तब समर्थित है जब प्रवृत्ति रेखा प्रकार exp, linear, या poly हो। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का समीकरण चार्ट पर (Rsquaredvalue के समान लेबल में) दिखाया जाए। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का समीकरण चार्ट पर (Rsquaredvalue के समान लेबल में) दिखाया जाए। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

बहुपद प्रवृत्ति रेखा का क्रम निर्दिष्ट करता है। यह अन्य प्रकारों के लिए अनदेखा किया जाता है। मान 2-और-6 के बीच होना चाहिए। पढ़ें/लिखें byte.

**रिटर्न:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

बहुपद प्रवृत्ति रेखा का क्रम निर्दिष्ट करता है। यह अन्य प्रकारों के लिए अनदेखा किया जाता है। मान 2-और-6 के बीच होना चाहिए। पढ़ें/लिखें byte.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

चल औसत प्रवृत्ति रेखा के लिए अवधि निर्दिष्ट करता है। यह अन्य विविधताओं के लिए अनदेखा किया जाता है। मान 2-और-255 के बीच होना चाहिए। पढ़ें/लिखें byte.

**रिटर्न:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

चल औसत प्रवृत्ति रेखा के लिए अवधि निर्दिष्ट करता है। यह अन्य विविधताओं के लिए अनदेखा किया जाता है। मान 2-और-255 के बीच होना चाहिए। पढ़ें/लिखें byte.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का R-स्क्वेयर मान चार्ट पर (समीकरण के समान लेबल में) दिखाया जाए। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

यह निर्दिष्ट करता है कि प्रवृत्ति रेखा का R-स्क्वेयर मान चार्ट पर (समीकरण के समान लेबल में) दिखाया जाए। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

इस प्रवृत्ति रेखा से संबंधित लेजेंड एंट्री। केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**रिटर्न:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

टेक्स्ट पैरामीटर "text" के साथ TextFrameForOverriding को आरम्भ करता है। यदि TextFrameForOverriding पहले से ही आरम्भ है तो केवल उसका टेक्स्ट बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नया TextFrameForOverriding के लिये टेक्स्ट। |

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

समृद्ध स्वरूपित टेक्स्ट रख सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह स्वरूपित टेक्स्ट मान डेटा लेबल के स्वचालित-जनित टेक्स्ट को ओवरराइड करता है। डेटा लेबल का स्वचालित-जनित टेक्स्ट वह होता है जो ShowSeriesName, ShowValue, ... प्रॉपर्टी द्वारा प्रबंधित होता है और TextFormatManager.TextFormat प्रॉपर्टी द्वारा स्वरूपित किया जाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

टेक्स्ट स्वरूप लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat)।

**रिटर्न:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

मूल चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat की मूल स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat की मूल प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)