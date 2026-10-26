---
title: IAxis
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक चार्ट के अक्ष को दर्शाने वाले ऑब्जेक्ट को संलग्न करता है।
type: docs
url: /hi/com.aspose.slides/iaxis/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

चार्ट के अक्ष का प्रतिनिधित्व करने वाले ऑब्जेक्ट को संलग्न करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | दर्शाता है कि वैल्यू एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच में पार करता है या नहीं। |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | दर्शाता है कि वैल्यू एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच में पार करता है या नहीं। |
| [getCrossAt()](#getCrossAt--) | एक्सिस पर वह बिंदु दर्शाता है जहाँ लम्ब एक्सिस इसे पार करता है। |
| [setCrossAt(float value)](#setCrossAt-float-) | एक्सिस पर वह बिंदु दर्शाता है जहाँ लम्ब एक्सिस इसे पार करता है। |
| [getDisplayUnit()](#getDisplayUnit--) | वैल्यू एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | वैल्यू एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। |
| [getActualMaxValue()](#getActualMaxValue--) | एक्सिस पर वास्तविक अधिकतम मान को निर्दिष्ट करता है। |
| [getActualMinValue()](#getActualMinValue--) | एक्सिस पर वास्तविक न्यूनतम मान को निर्दिष्ट करता है। |
| [getActualMajorUnit()](#getActualMajorUnit--) | एक्सिस की वास्तविक प्रमुख इकाई को निर्दिष्ट करता है। |
| [getActualMinorUnit()](#getActualMinorUnit--) | एक्सिस की वास्तविक गौण इकाई को निर्दिष्ट करता है। |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | एक्सिस के वास्तविक प्रमुख इकाई स्केल को निर्दिष्ट करता है। |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | एक्सिस के वास्तविक गौण इकाई स्केल को निर्दिष्ट करता है। |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | बताता है कि अधिकतम मान स्वचालित रूप से सौंपा गया है या नहीं। |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | बताता है कि अधिकतम मान स्वचालित रूप से सौंपा गया है या नहीं। |
| [getMaxValue()](#getMaxValue--) | वैल्यू एक्सिस पर अधिकतम मान को दर्शाता है। |
| [setMaxValue(double value)](#setMaxValue-double-) | वैल्यू एक्सिस पर अधिकतम मान को दर्शाता है। |
| [getMinorUnit()](#getMinorUnit--) | तारीख या वैल्यू एक्सिस के लिए गौण इकाइयों को दर्शाता है। |
| [setMinorUnit(double value)](#setMinorUnit-double-) | तारीख या वैल्यू एक्सिस के लिए गौण इकाइयों को दर्शाता है। |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | बताता है कि एक्सिस की गौण इकाई स्वचालित रूप से सौंपी गई है या नहीं। |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | बताता है कि एक्सिस की गौण इकाई स्वचालित रूप से सौंपी गई है या नहीं। |
| [getMajorUnit()](#getMajorUnit--) | तारीख या वैल्यू एक्सिस के लिए प्रमुख इकाइयों को दर्शाता है। |
| [setMajorUnit(double value)](#setMajorUnit-double-) | तारीख या वैल्यू एक्सिस के लिए प्रमुख इकाइयों को दर्शाता है। |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | बताता है कि एक्सिस की प्रमुख इकाई स्वचालित रूप से सौंपी गई है या नहीं। |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | बताता है कि एक्सिस की प्रमुख इकाई स्वचालित रूप से सौंपी गई है या नहीं। |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | बताता है कि न्यूनतम मान स्वचालित रूप से सौंपा गया है या नहीं। |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | बताता है कि न्यूनतम मान स्वचालित रूप से सौंपा गया है या नहीं। |
| [getMinValue()](#getMinValue--) | वैल्यू एक्सिस पर न्यूनतम मान को दर्शाता है। |
| [setMinValue(double value)](#setMinValue-double-) | वैल्यू एक्सिस पर न्यूनतम मान को दर्शाता है। |
| [isLogarithmic()](#isLogarithmic--) | बताता है कि वैल्यू एक्सिस का स्केल प्रकार लॉगरिदमिक है या नहीं। |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | बताता है कि वैल्यू एक्सिस का स्केल प्रकार लॉगरिदमिक है या नहीं। |
| [getLogBase()](#getLogBase--) | लॉगरिदमिक बेस को दर्शाता है। |
| [setLogBase(double value)](#setLogBase-double-) | लॉगरिदमिक बेस को दर्शाता है। |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | बताता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से पहला क्रम में प्लॉट करता है या नहीं। |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | बताता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से पहला क्रम में प्लॉट करता है या नहीं। |
| [isVisible()](#isVisible--) | बताता है कि अक्ष दृश्यमान है या नहीं। |
| [setVisible(boolean value)](#setVisible-boolean-) | बताता है कि अक्ष दृश्यमान है या नहीं। |
| [getMajorTickMark()](#getMajorTickMark--) | निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क प्रकार को दर्शाता है। |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क प्रकार को दर्शाता है। |
| [getMinorTickMark()](#getMinorTickMark--) | निर्दिष्ट अक्ष के लिए गौण टिक मार्क प्रकार को दर्शाता है। |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | निर्दिष्ट अक्ष के लिए गौण टिक मार्क प्रकार को दर्शाता है। |
| [getTickLabelPosition()](#getTickLabelPosition--) | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति को दर्शाता है। |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति को दर्शाता है। |
| [getMajorUnitScale()](#getMajorUnitScale--) | तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। |
| [getMinorUnitScale()](#getMinorUnitScale--) | तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। |
| [getBaseUnitScale()](#getBaseUnitScale--) | तारीख अक्ष पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | तारीख अक्ष पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | चार्ट अक्ष पर गौण ग्रिडलाइन फ़ॉर्मेट को दर्शाता है। |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | चार्ट अक्ष पर प्रमुख ग्रिडलाइन फ़ॉर्मेट को दर्शाता है। |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | बताता है कि गौण ग्रिडलाइन दिखाए गए हैं या नहीं। |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | बताता है कि प्रमुख ग्रिडलाइन दिखाए गए हैं या नहीं। |
| [getFormat()](#getFormat--) | अक्ष का फ़ॉर्मेट दर्शाता है। |
| [getTitle()](#getTitle--) | अक्ष का शीर्षक प्राप्त करता है। |
| [getCrossType()](#getCrossType--) | निर्धारित अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, वहाँ के CrossType को दर्शाता है। |
| [setCrossType(int value)](#setCrossType-int-) | निर्धारित अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, वहाँ के CrossType को दर्शाता है। |
| [getPosition()](#getPosition--) | अक्ष की स्थिति को दर्शाता है। |
| [setPosition(int value)](#setPosition-int-) | अक्ष की स्थिति को दर्शाता है। |
| [hasTitle()](#hasTitle--) | निर्धारित करता है कि क्या अक्ष का दृश्य शीर्षक है। |
| [setTitle(boolean value)](#setTitle-boolean-) | निर्धारित करता है कि क्या अक्ष का दृश्य शीर्षक है। |
| [getNumberFormat()](#getNumberFormat--) | अक्ष लेबल्स के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | अक्ष लेबल्स के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | बताता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | बताता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | टिक लेबल्स का घूर्णन कोण दर्शाता है। पढ़ें/लिखें float। |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | टिक लेबल्स का घूर्णन कोण दर्शाता है। पढ़ें/लिखें float। |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | बनाए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | बनाए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | स्वचलित टिक लेबल स्पेसिंग मान को निर्दिष्ट करता है। |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | स्वचलित टिक लेबल स्पेसिंग मान को निर्दिष्ट करता है। |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | अगले टिक मार्क को ड्रॉ करने से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | अगले टिक मार्क को ड्रॉ करने से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | स्वचलित टिक मार्क स्पेसिंग मान को निर्दिष्ट करता है। |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | स्वचलित टिक मार्क स्पेसिंग मान को निर्दिष्ट करता है। |
| [getLabelOffset()](#getLabelOffset--) | अक्ष से लेबल्स की दूरी को निर्दिष्ट करता है। |
| [setLabelOffset(int value)](#setLabelOffset-int-) | अक्ष से लेबल्स की दूरी को निर्दिष्ट करता है। |
| [getCategoryAxisType()](#getCategoryAxisType--) | श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | IAxis.CategoryAxisType प्रॉपर्टी को अक्ष डेटा के आधार पर स्वचालित रूप से निर्धारित मान से सेट करता है। |
| [getAggregationType()](#getAggregationType--) | श्रेणी अक्ष का एग्रीगेशन प्रकार (बिनिंग) दर्शाता है। |
| [setAggregationType(int value)](#setAggregationType-int-) | श्रेणी अक्ष का एग्रीगेशन प्रकार (बिनिंग) दर्शाता है। |
| [getBinWidth()](#getBinWidth--) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट हो, तब बिन चौड़ाई को निर्दिष्ट करता है। |
| [setBinWidth(double value)](#setBinWidth-double-) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट हो, तब बिन चौड़ाई को निर्दिष्ट करता है। |
| [getNumberOfBins()](#getNumberOfBins--) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तब बिन्स की संख्या को निर्दिष्ट करता है। |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तब बिन्स की संख्या को निर्दिष्ट करता है। |
| [isOverflowBin()](#isOverflowBin--) | बताता है कि ओवरफ़्लो बिन लागू है या नहीं। |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | बताता है कि ओवरफ़्लो बिन लागू है या नहीं। |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | स्वचलित ओवरफ़्लो बिन मान को निर्दिष्ट करता है। |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | स्वचलित ओवरफ़्लो बिन मान को निर्दिष्ट करता है। |
| [getOverflowBin()](#getOverflowBin--) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setOverflowBin(double value)](#setOverflowBin-double-) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [isUnderflowBin()](#isUnderflowBin--) | बताता है कि अंडरफ़्लो बिन लागू है या नहीं। |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | बताता है कि अंडरफ़्लो बिन लागू है या नहीं। |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | स्वचलित अंडरफ़्लो बिन मान को निर्दिष्ट करता है। |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | स्वचलित अंडरफ़्लो बिन मान को निर्दिष्ट करता है। |
| [getUnderflowBin()](#getUnderflowBin--) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

दर्शाता है कि वैल्यू एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच में पार करता है या नहीं। यह प्रॉपर्टी केवल श्रेणी एक्सिस पर लागू होती है, और 3-डी चार्ट पर लागू नहीं होती। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

दर्शाता है कि वैल्यू एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच में पार करता है या नहीं। यह प्रॉपर्टी केवल श्रेणी एक्सिस पर लागू होती है, और 3-डी चार्ट पर लागू नहीं होती। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

एक्सिस पर वह बिंदु दर्शाता है जहाँ लम्ब एक्सिस इसे पार करता है। पढ़ें/लिखें float.

**वापसी:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

एक्सिस पर वह बिंदु दर्शाता है जहाँ लम्ब एक्सिस इसे पार करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

वैल्यू एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। पढ़ें/लिखें [DisplayUnitType](../../com.aspose.slides/displayunittype).

**वापसी:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

वैल्यू एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। पढ़ें/लिखें [DisplayUnitType](../../com.aspose.slides/displayunittype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

एक्सिस पर वास्तविक अधिकतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**वापसी:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

एक्सिस पर वास्तविक न्यूनतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**वापसी:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

एक्सिस की वास्तविक प्रमुख इकाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**वापसी:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

एक्सिस की वास्तविक गौण इकाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**वापसी:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

एक्सिस के वास्तविक प्रमुख इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**वापसी:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

एक्सिस के वास्तविक गौण इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**वापसी:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

बताता है कि अधिकतम मान स्वचालित रूप से सौंपा गया है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

बताता है कि अधिकतम मान स्वचालित रूप से सौंपा गया है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

वैल्यू एक्सिस पर अधिकतम मान को दर्शाता है। पढ़ें/लिखें double.

**वापसी:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

वैल्यू एक्सिस पर अधिकतम मान को दर्शाता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

तारीख या वैल्यू एक्सिस के लिए गौण इकाइयों को दर्शाता है। पढ़ें/लिखें double.

**वापसी:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

तारीख या वैल्यू एक्सिस के लिए गौण इकाइयों को दर्शाता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

बताता है कि एक्सिस की गौण इकाई स्वचालित रूप से सौंपी गई है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

बताता है कि एक्सिस की गौण इकाई स्वचालित रूप से सौंपी गई है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

तारीख या वैल्यू एक्सिस के लिए प्रमुख इकाइयों को दर्शाता है। पढ़ें/लिखें double.

**वापसी:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

तारीख या वैल्यू एक्सिस के लिए प्रमुख इकाइयों को दर्शाता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

बताता है कि एक्सिस की प्रमुख इकाई स्वचालित रूप से सौंपी गई है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

बताता है कि एक्सिस की प्रमुख इकाई स्वचालित रूप से सौंपी गई है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

बताता है कि न्यूनतम मान स्वचालित रूप से सौंपा गया है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

बताता है कि न्यूनतम मान स्वचालित रूप से सौंपा गया है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

वैल्यू एक्सिस पर न्यूनतम मान को दर्शाता है। पढ़ें/लिखें double.

**वापसी:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

वैल्यू एक्सिस पर न्यूनतम मान को दर्शाता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

बताता है कि वैल्यू एक्सिस स्केल प्रकार लॉगरिदमिक है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

बताता है कि वैल्यू एक्सिस स्केल प्रकार लॉगरिदमिक है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

लॉगरिदमिक बेस को दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ें/लिखें double.

**वापसी:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

लॉगरिदमिक बेस को दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

बताता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से पहला क्रम में प्लॉट करता है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

बताता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से पहला क्रम में प्लॉट करता है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

बताता है कि अक्ष दृश्यमान है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

बताता है कि अक्ष दृश्यमान है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क प्रकार को दर्शाता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**वापसी:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क प्रकार को दर्शाता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

निर्दिष्ट अक्ष के लिए गौण टिक मार्क प्रकार को दर्शाता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**वापसी:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

निर्दिष्ट अक्ष के लिए गौण टिक मार्क प्रकार को दर्शाता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति को दर्शाता है। पढ़ें/लिखें [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**वापसी:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति को दर्शाता है। पढ़ें/लिखें [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**वापसी:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**वापसी:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

तारीख अक्ष पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**वापसी:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

तारीख अक्ष पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

चार्ट अक्ष पर गौण ग्रिडलाइन फ़ॉर्मेट को दर्शाता है। केवल-पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**वापसी:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

चार्ट अक्ष पर प्रमुख ग्रिडलाइन फ़ॉर्मेट को दर्शाता है। केवल-पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**वापसी:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

बताता है कि गौण ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

बताता है कि प्रमुख ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

अक्ष का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [IAxisFormat](../../com.aspose.slides/iaxisformat).

**वापसी:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

अक्ष का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle).

**वापसी:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

निर्दिष्ट अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, वहाँ के CrossType को दर्शाता है। पढ़ें/लिखें [CrossesType](../../com.aspose.slides/crossestype).

**वापसी:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

निर्दिष्ट अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, वहाँ के CrossType को दर्शाता है। पढ़ें/लिखें [CrossesType](../../com.aspose.slides/crossestype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

अक्ष की स्थिति को दर्शाता है। पढ़ें/लिखें [AxisPositionType](../../com.aspose.slides/axispositiontype).

**वापसी:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

अक्ष की स्थिति को दर्शाता है। पढ़ें/लिखें [AxisPositionType](../../com.aspose.slides/axispositiontype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

निर्धारित करता है कि क्या अक्ष का दृश्य शीर्षक है। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

निर्धारित करता है कि क्या अक्ष का दृश्य शीर्षक है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

अक्ष लेबल्स के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

अक्ष लेबल्स के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

बताता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

बताता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

टिक लेबल्स का घूर्णन कोण दर्शाता है। पढ़ें/लिखें float.

**वापसी:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

टिक लेबल्स का घूर्णन कोण दर्शाता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

बनाए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। पढ़ें/लिखें long.

**वापसी:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

बनाए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। पढ़ें/लिखें long.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

स्वचलित टिक लेबल स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickLabelSpacing प्रॉपर्टी का प्रयोग करें। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

स्वचलित टिक लेबल स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickLabelSpacing प्रॉपर्टी का प्रयोग करें। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

कितने टिक मार्क छोड़ने हैं, इससे पहले कि अगला ड्रॉ हो। श्रेणी या श्रृंखला अक्ष पर लागू। पढ़ें/लिखें int.

**वापसी:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

कितने टिक मार्क छोड़ने हैं, इससे पहले कि अगला ड्रॉ हो। श्रेणी या श्रृंखला अक्ष पर लागू। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

स्वचलित टिक मार्क स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickMarksSpacing प्रॉपर्टी का प्रयोग करें। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

स्वचलित टिक मार्क स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickMarksSpacing प्रॉपर्टी का प्रयोग करें। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

लेबल्स की दूरी को अक्ष से निर्दिष्ट करता है। श्रेणी या तारीख अक्ष पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ें/लिखें int.

**वापसी:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

लेबल्स की दूरी को अक्ष से निर्दिष्ट करता है। श्रेणी या तारीख अक्ष पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**वापसी:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType प्रॉपर्टी को अक्ष डेटा के आधार पर स्वचालित रूप से निर्धारित मान से सेट करता है।

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

श्रेणी अक्ष का एग्रीगेशन प्रकार (बिनिंग) दर्शाता है। श्रेणी पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**वापसी:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

श्रेणी अक्ष का एग्रीगेशन प्रकार (बिनिंग) दर्शाता है। श्रेणी पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट हो, तब बिन चौड़ाई को निर्दिष्ट करता है। श्रेणी अक्ष पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**वापसी:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट हो, तब बिन चौड़ाई को निर्दिष्ट करता है। श्रेणी अक्ष पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तब बिन्स की संख्या को निर्दिष्ट करता है। श्रेणी अक्ष पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**वापसी:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तब बिन्स की संख्या को निर्दिष्ट करता है। श्रेणी अक्ष पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

बताता है कि ओवरफ़्लो बिन लागू है या नहीं। IsAutomaticOverflowBin और OverflowBin का उपयोग कर ओवरफ़्लो बिन मान को समायोजित करें।

**वापसी:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

बताता है कि ओवरफ़्लो बिन लागू है या नहीं। IsAutomaticOverflowBin और OverflowBin का उपयोग कर ओवरफ़्लो बिन मान को समायोजित करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

स्वचलित ओवरफ़्लो बिन मान को निर्दिष्ट करता है। यदि false: OverflowBin प्रॉपर्टी का प्रयोग करें।

**वापसी:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

स्वचलित ओवरफ़्लो बिन मान को निर्दिष्ट करता है। यदि false: OverflowBin प्रॉपर्टी का प्रयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin प्रॉपर्टी false और IsOverflowBin प्रॉपर्टी true हो।

**वापसी:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin प्रॉपर्टी false और IsOverflowBin प्रॉपर्टी true हो।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

बताता है कि अंडरफ़्लो बिन लागू है या नहीं। IsAutomaticUnderflowBin और UnderflowBin का उपयोग कर अंडरफ़्लो बिन मान को समायोजित करें।

**वापसी:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

बताता है कि अंडरफ़्लो बिन लागू है या नहीं। IsAutomaticUnderflowBin और UnderflowBin का उपयोग कर अंडरफ़्लो बिन मान को समायोजित करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

स्वचलित अंडरफ़्लो बिन मान को निर्दिष्ट करता है। यदि false: UnderflowBin प्रॉपर्टी का प्रयोग करें।

**वापसी:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

स्वचलित अंडरफ़्लो बिन मान को निर्दिष्ट करता है। यदि false: UnderflowBin प्रॉपर्टी का प्रयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin प्रॉपर्टी false और IsUnderflowBin प्रॉपर्टी true हो।

**वापसी:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin प्रॉपर्टी false और IsUnderflowBin प्रॉपर्टी true हो।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |