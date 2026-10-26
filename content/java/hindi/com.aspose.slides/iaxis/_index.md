---
title: IAxis
second_title: Aspose.Slides for Java API संदर्भ
description: चार्ट अक्ष का प्रतिनिधित्व करने वाले वस्तु को संलग्न करता है।
type: docs
url: /hi/com.aspose.slides/iaxis/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

ऐसे ऑब्जेक्ट को सम्मिलित करता है जो चार्ट की धुरी को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | निर्देशित करता है कि मान धुरी श्रेणी धुरी को श्रेणियों के बीच काटती है या नहीं। |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | निर्देशित करता है कि मान धुरी श्रेणी धुरी को श्रेणियों के बीच काटती है या नहीं। |
| [getCrossAt()](#getCrossAt--) | निर्देशित करता है वह बिंदु जहाँ लम्बवत धुरी इसे काटती है। |
| [setCrossAt(float value)](#setCrossAt-float-) | निर्देशित करता है वह बिंदु जहाँ लम्बवत धुरी इसे काटती है। |
| [getDisplayUnit()](#getDisplayUnit--) | मान धुरी के लिए प्रदर्शन इकाइयों का स्केलिंग मान निर्दिष्ट करता है। |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | मान धुरी के लिए प्रदर्शन इकाइयों का स्केलिंग मान निर्दिष्ट करता है। |
| [getActualMaxValue()](#getActualMaxValue--) | धुरी पर वास्तविक अधिकतम मान निर्दिष्ट करता है। |
| [getActualMinValue()](#getActualMinValue--) | धुरी पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। |
| [getActualMajorUnit()](#getActualMajorUnit--) | धुरी की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। |
| [getActualMinorUnit()](#getActualMinorUnit--) | धुरी की वास्तविक लघु इकाई निर्दिष्ट करता है। |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | धुरी के वास्तविक प्रमुख इकाई स्केल को निर्दिष्ट करता है। |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | धुरी के वास्तविक लघु इकाई स्केल को निर्दिष्ट करता है। |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | निर्देशित करता है कि अधिकतम मान स्वतः सौंपा गया है या नहीं। |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | निर्देशित करता है कि अधिकतम मान स्वतः सौंपा गया है या नहीं। |
| [getMaxValue()](#getMaxValue--) | मान धुरी पर अधिकतम मान को दर्शाता है। |
| [setMaxValue(double value)](#setMaxValue-double-) | मान धुरी पर अधिकतम मान को दर्शाता है। |
| [getMinorUnit()](#getMinorUnit--) | तारीख या मान धुरी के लिए लघु इकाइयाँ दर्शाता है। |
| [setMinorUnit(double value)](#setMinorUnit-double-) | तारीख या मान धुरी के लिए लघु इकाइयाँ दर्शाता है। |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | निर्देशित करता है कि धुरी की लघु इकाई स्वतः सौंपा गया है या नहीं। |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | निर्देशित करता है कि धुरी की लघु इकाई स्वतः सौंपा गया है या नहीं। |
| [getMajorUnit()](#getMajorUnit--) | तारीख या मान धुरी के लिए प्रमुख इकाइयाँ दर्शाता है। |
| [setMajorUnit(double value)](#setMajorUnit-double-) | तारीख या मान धुरी के लिए प्रमुख इकाइयाँ दर्शाता है। |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | निर्देशित करता है कि धुरी की प्रमुख इकाई स्वतः सौंपा गया है या नहीं। |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | निर्देशित करता है कि धुरी की प्रमुख इकाई स्वतः सौंपा गया है या नहीं। |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | निर्देशित करता है कि न्यूनतम मान स्वतः सौंपा गया है या नहीं। |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | निर्देशित करता है कि न्यूनतम मान स्वतः सौंपा गया है या नहीं। |
| [getMinValue()](#getMinValue--) | मान धुरी पर न्यूनतम मान को दर्शाता है। |
| [setMinValue(double value)](#setMinValue-double-) | मान धुरी पर न्यूनतम मान को दर्शाता है। |
| [isLogarithmic()](#isLogarithmic--) | निर्देशित करता है कि मान धुरी का स्केल प्रकार लघुगणकीय है या नहीं। |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | निर्देशित करता है कि मान धुरी का स्केल प्रकार लघुगणकीय है या नहीं। |
| [getLogBase()](#getLogBase--) | लघुगणकीय आधार को दर्शाता है। |
| [setLogBase(double value)](#setLogBase-double-) | लघुगणकीय आधार को दर्शाता है। |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | निर्देशित करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | निर्देशित करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। |
| [isVisible()](#isVisible--) | निर्देशित करता है कि धुरी दृश्यमान है या नहीं। |
| [setVisible(boolean value)](#setVisible-boolean-) | निर्देशित करता है कि धुरी दृश्यमान है या नहीं। |
| [getMajorTickMark()](#getMajorTickMark--) | निर्दिष्ट धुरी के प्रमुख टिक मार्क का प्रकार दर्शाता है। |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | निर्दिष्ट धुरी के प्रमुख टिक मार्क का प्रकार दर्शाता है। |
| [getMinorTickMark()](#getMinorTickMark--) | निर्दिष्ट धुरी के लघु टिक मार्क का प्रकार दर्शाता है। |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | निर्दिष्ट धुरी के लघु टिक मार्क का प्रकार दर्शाता है। |
| [getTickLabelPosition()](#getTickLabelPosition--) | निर्दिष्ट धुरी पर टिक-मार्क लेबल की स्थिति दर्शाता है। |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | निर्दिष्ट धुरी पर टिक-मार्क लेबल की स्थिति दर्शाता है। |
| [getMajorUnitScale()](#getMajorUnitScale--) | तारीख धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | तारीख धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [getMinorUnitScale()](#getMinorUnitScale--) | तारीख धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | तारीख धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [getBaseUnitScale()](#getBaseUnitScale--) | तारीख धुरी पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | तारीख धुरी पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | चार्ट धुरी पर लघु ग्रिडलाइन स्वरूप दर्शाता है। |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | चार्ट धुरी पर प्रमुख ग्रिडलाइन स्वरूप दर्शाता है। |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | निर्देशित करता है कि लघु ग्रिडलाइन दिखाए गए हैं या नहीं। |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | निर्देशित करता है कि प्रमुख ग्रिडलाइन दिखाए गए हैं या नहीं। |
| [getFormat()](#getFormat--) | धुरी के स्वरूप को दर्शाता है। |
| [getTitle()](#getTitle--) | धुरी का शीर्षक प्राप्त करता है। |
| [getCrossType()](#getCrossType--) | निर्दिष्ट धुरी पर जहाँ अन्य धुरी काटती है, उस स्थान का CrossType दर्शाता है। |
| [setCrossType(int value)](#setCrossType-int-) | निर्दिष्ट धुरी पर जहाँ अन्य धुरी काटती है, उस स्थान का CrossType दर्शाता है। |
| [getPosition()](#getPosition--) | धुरी की स्थिति दर्शाता है। |
| [setPosition(int value)](#setPosition-int-) | धुरी की स्थिति दर्शाता है। |
| [hasTitle()](#hasTitle--) | निर्धारित करता है कि धुरी का शीर्षक दृश्यमान है या नहीं। |
| [setTitle(boolean value)](#setTitle-boolean-) | निर्धारित करता है कि धुरी का शीर्षक दृश्यमान है या नहीं। |
| [getNumberFormat()](#getNumberFormat--) | धुरी लेबल के प्रारूप स्ट्रिंग को दर्शाता है। |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | धुरी लेबल के प्रारूप स्ट्रिंग को दर्शाता है। |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | निर्देशित करता है कि स्वरूप स्रोत डेटा से जुड़ा है या नहीं। |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | निर्देशित करता है कि स्वरूप स्रोत डेटा से जुड़ा है या नहीं। |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | टिक लेबल के घूर्णन कोण को दर्शाता है। पढ़ें/लिखें फ़्लोट। |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | टिक लेबल के घूर्णन कोण को दर्शाता है। पढ़ें/लिखें फ़्लोट। |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | निर्दिष्ट करता है कि खींचे गए लेबल के बीच कितने टिक लेबल छोड़ने हैं। |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | निर्दिष्ट करता है कि खींचे गए लेबल के बीच कितने टिक लेबल छोड़ने हैं। |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | अगला टिक मार्क खींचे जाने से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | अगला टिक मार्क खींचे जाने से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | स्वचालित टिक मार्क स्पेसिंग मान निर्दिष्ट करता है। |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | स्वचालित टिक मार्क स्पेसिंग मान निर्दिष्ट करता है। |
| [getLabelOffset()](#getLabelOffset--) | लेबल की धुरी से दूरी निर्दिष्ट करता है। |
| [setLabelOffset(int value)](#setLabelOffset-int-) | लेबल की धुरी से दूरी निर्दिष्ट करता है। |
| [getCategoryAxisType()](#getCategoryAxisType--) | श्रेणी धुरी का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | श्रेणी धुरी का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | धुरी डेटा के आधार पर स्वचालित रूप से निर्धारित मान के साथ IAxis.CategoryAxisType संपत्ति को सेट करता है। |
| [getAggregationType()](#getAggregationType--) | श्रेणी धुरी का एकत्रीकरण प्रकार (बिनिंग) दर्शाता है। |
| [setAggregationType(int value)](#setAggregationType-int-) | श्रेणी धुरी का एकत्रीकरण प्रकार (बिनिंग) दर्शाता है। |
| [getBinWidth()](#getBinWidth--) | जब AggregationType संपत्ति मान AxisAggregationType.ByBinWidth पर सेट हो, तो बिन की चौड़ाई निर्दिष्ट करता है। |
| [setBinWidth(double value)](#setBinWidth-double-) | जब AggregationType संपत्ति मान AxisAggregationType.ByBinWidth पर सेट हो, तो बिन की चौड़ाई निर्दिष्ट करता है। |
| [getNumberOfBins()](#getNumberOfBins--) | जब AggregationType संपत्ति मान AxisAggregationType.ByNumberOfBins पर सेट हो, तो बिनों की संख्या निर्दिष्ट करता है। |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | जब AggregationType संपत्ति मान AxisAggregationType.ByNumberOfBins पर सेट हो, तो बिनों की संख्या निर्दिष्ट करता है। |
| [isOverflowBin()](#isOverflowBin--) | निर्देशित करता है कि ओवरफ़्लो बिन लागू किया गया है या नहीं। |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | निर्देशित करता है कि ओवरफ़्लो बिन लागू किया गया है या नहीं। |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। |
| [getOverflowBin()](#getOverflowBin--) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setOverflowBin(double value)](#setOverflowBin-double-) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [isUnderflowBin()](#isUnderflowBin--) | निर्देशित करता है कि अंडरफ़्लो बिन लागू किया गया है या नहीं। |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | निर्देशित करता है कि अंडरफ़्लो बिन लागू किया गया है या नहीं। |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। |
| [getUnderflowBin()](#getUnderflowBin--) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

निर्देशित करता है कि मान धुरी श्रेणी धुरी को श्रेणियों के बीच काटती है या नहीं। यह गुण केवल श्रेणी धुरी पर लागू होता है, और यह 3-D चार्ट पर लागू नहीं होता। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

निर्देशित करता है कि मान धुरी श्रेणी धुरी को श्रेणियों के बीच काटती है या नहीं। यह गुण केवल श्रेणी धुरी पर लागू होता है, और यह 3-D चार्ट पर लागू नहीं होता। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

निर्दिष्ट करता है वह बिंदु जहाँ लम्बवत धुरी इसे काटती है। पढ़ें/लिखें फ़्लोट।

**वापसी:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

निर्दिष्ट करता है वह बिंदु जहाँ लम्बवत धुरी इसे काटती है। पढ़ें/लिखें फ़्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

मान धुरी के लिए प्रदर्शन इकाइयों का स्केलिंग मान निर्दिष्ट करता है। पढ़ें/लिखें [DisplayUnitType](../../com.aspose.slides/displayunittype)।

**वापसी:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

मान धुरी के लिए प्रदर्शन इकाइयों का स्केलिंग मान निर्दिष्ट करता है। पढ़ें/लिखें [DisplayUnitType](../../com.aspose.slides/displayunittype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

धुरी पर वास्तविक अधिकतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें।

**वापसी:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

धुरी पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें।

**वापसी:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

धुरी की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें।

**वापसी:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

धुरी की वास्तविक लघु इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें।

**वापसी:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

धुरी के वास्तविक प्रमुख इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें।

**वापसी:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

धुरी के वास्तविक लघु इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें।

**वापसी:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

निर्देशित करता है कि अधिकतम मान स्वतः सौंपा गया है या नहीं। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

निर्देशित करता है कि अधिकतम मान स्वतः सौंपा गया है या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

मान धुरी पर अधिकतम मान को दर्शाता है। पढ़ें/लिखें डबल।

**वापसी:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

मान धुरी पर अधिकतम मान को दर्शाता है। पढ़ें/लिखें डबल।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

तारीख या मान धुरी के लिए लघु इकाइयाँ दर्शाता है। पढ़ें/लिखें डबल।

**वापसी:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

तारीख या मान धुरी के लिए लघु इकाइयाँ दर्शाता है। पढ़ें/लिखें डबल।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

निर्देशित करता है कि धुरी की लघु इकाई स्वतः सौंपा गया है या नहीं। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

निर्देशित करता है कि धुरी की लघु इकाई स्वतः सौंपा गया है या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

तारीख या मान धुरी के लिए प्रमुख इकाइयाँ दर्शाता है। पढ़ें/लिखें डबल।

**वापसी:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

तारीख या मान धुरी के लिए प्रमुख इकाइयाँ दर्शाता है। पढ़ें/लिखें डबल।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

निर्देशित करता है कि धुरी की प्रमुख इकाई स्वतः सौंपा गया है या नहीं। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

सूचित करता है कि क्या एक्सिस की प्रमुख इकाई स्वचालित रूप से नियत की गई है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

सूचित करता है कि क्या न्यूनतम मान स्वचालित रूप से नियत किया गया है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

सूचित करता है कि क्या न्यूनतम मान स्वचालित रूप से नियत किया गया है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

मूल्य एक्सिस पर न्यूनतम मान का प्रतिनिधित्व करता है। पढ़ें/लिखें double.

**रिटर्न:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

मूल्य एक्सिस पर न्यूनतम मान का प्रतिनिधित्व करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

सूचित करता है कि क्या मूल्य एक्सिस स्केल प्रकार लघुगणकीय है या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

सूचित करता है कि क्या मूल्य एक्सिस स्केल प्रकार लघुगणकीय है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

लघुगणकीय आधार का प्रतिनिधित्व करता है। डिफ़ॉल्ट मान 10 है। पढ़ें/लिखें double.

**रिटर्न:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

लघुगणकीय आधार का प्रतिनिधित्व करता है। डिफ़ॉल्ट मान 10 है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

सूचित करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से पहले क्रम में प्लॉट करता है या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

सूचित करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से पहले क्रम में प्लॉट करता है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

सूचित करता है कि एक्सिस दृश्यमान है या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

सूचित करता है कि एक्सिस दृश्यमान है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

निर्दिष्ट एक्सिस के लिए प्रमुख टिक मार्क प्रकार का प्रतिनिधित्व करता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**रिटर्न:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

निर्दिष्ट एक्सिस के लिए प्रमुख टिक मार्क प्रकार का प्रतिनिधित्व करता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

निर्दिष्ट एक्सिस के लिए लघु टिक मार्क प्रकार का प्रतिनिधित्व करता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**रिटर्न:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

निर्दिष्ट एक्सिस के लिए लघु टिक मार्क प्रकार का प्रतिनिधित्व करता है। पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

निर्दिष्ट एक्सिस पर टिक-मार्क लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ें/लिखें [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**रिटर्न:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

निर्दिष्ट एक्सिस पर टिक-मार्क लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ें/लिखें [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

डेट एक्सिस के लिए प्रमुख इकाई स्केल का प्रतिनिधित्व करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**रिटर्न:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

डेट एक्सिस के लिए प्रमुख इकाई स्केल का प्रतिनिधित्व करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

डेट एक्सिस के लिए प्रमुख इकाई स्केल का प्रतिनिधित्व करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**रिटर्न:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

डेट एक्सिस के लिए प्रमुख इकाई स्केल का प्रतिनिधित्व करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

डेट एक्सिस पर प्रस्तुत सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**रिटर्न:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

डेट एक्सिस पर प्रस्तुत सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

चार्ट एक्सिस पर लघु ग्रिडलाइन फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**रिटर्न:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

चार्ट एक्सिस पर प्रमुख ग्रिडलाइन फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**रिटर्न:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

सूचित करता है कि लघु ग्रिडलाइन दिखेगी या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

सूचित करता है कि प्रमुख ग्रिडलाइन दिखेगी या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

एक्सिस का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [IAxisFormat](../../com.aspose.slides/iaxisformat).

**रिटर्न:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

एक्सिस का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle).

**रिटर्न:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

निर्दिष्ट एक्सिस पर अन्य एक्सिस के क्रॉस के स्थान पर CrossType का प्रतिनिधित्व करता है। पढ़ें/लिखें [CrossesType](../../com.aspose.slides/crossestype).

**रिटर्न:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

निर्दिष्ट एक्सिस पर अन्य एक्सिस के क्रॉस के स्थान पर CrossType का प्रतिनिधित्व करता है। पढ़ें/लिखें [CrossesType](../../com.aspose.slides/crossestype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

एक्सिस की स्थिति दर्शाता है। पढ़ें/लिखें [AxisPositionType](../../com.aspose.slides/axispositiontype).

**रिटर्न:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

एक्सिस की स्थिति दर्शाता है। पढ़ें/लिखें [AxisPositionType](../../com.aspose.slides/axispositiontype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

निर्धारित करता है कि क्या एक्सिस का एक दृश्यमान शीर्षक है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

निर्धारित करता है कि क्या एक्सिस का एक दृश्यमान शीर्षक है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

एक्सिस लेबल के फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

एक्सिस लेबल के फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

निर्दिष्ट करता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

निर्दिष्ट करता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

टिक लेबल की घूर्णन कोण का प्रतिनिधित्व करता है। पढ़ें/लिखें float.

**रिटर्न:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

टिक लेबल की घूर्णन कोण का प्रतिनिधित्व करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

निर्दिष्ट करता है कि ड्रॉ किए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ें। पढ़ें/लिखें long.

**रिटर्न:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

निर्दिष्ट करता है कि ड्रॉ किए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ें। पढ़ें/लिखें long.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

स्वचालित टिक लेबल स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickLabelSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

स्वचालित टिक लेबल स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickLabelSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

अगले टिक मार्क को ड्रॉ करने से पहले कितने टिक मार्क छोड़ें, इसे निर्दिष्ट करता है। श्रेणी या श्रृंखला एक्सिस पर लागू। पढ़ें/लिखें int.

**रिटर्न:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

अगले टिक मार्क को ड्रॉ करने से पहले कितने टिक मार्क छोड़ें, इसे निर्दिष्ट करता है। श्रेणी या श्रृंखला एक्सिस पर लागू। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

स्वचालित टिक मार्क स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickMarksSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

स्वचालित टिक मार्क स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickMarksSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

लेबल को एक्सिस से दूरी निर्दिष्ट करता है। श्रेणी या तिथि एक्सिस पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ें/लिखें int.

**रिटर्न:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

लेबल को एक्सिस से दूरी निर्दिष्ट करता है। श्रेणी या तिथि एक्सिस पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

श्रेणी एक्सिस के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**रिटर्न:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

श्रेणी एक्सिस के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType प्रॉपर्टी को एक ऐसे मान के साथ सेट करता है जो एक्सिस डेटा के आधार पर स्वचालित रूप से निर्धारित होता है।

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

श्रेणी एक्सिस (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। श्रेणी पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**रिटर्न:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

श्रेणी एक्सिस (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। श्रेणी पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

निर्दिष्ट करता है बिन चौड़ाई जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByBinWidth पर सेट हो। श्रेणी अक्ष पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**रिटर्न मान:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

निर्दिष्ट करता है बिन चौड़ाई जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByBinWidth पर सेट हो। श्रेणी अक्ष पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

निर्दिष्ट करता है बिनों की संख्या जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByNumberOfBins पर सेट हो। श्रेणी अक्ष पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**रिटर्न मान:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

निर्दिष्ट करता है बिनों की संख्या जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByNumberOfBins पर सेट हो। श्रेणी अक्ष पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

निर्दिष्ट करता है कि ओवरफ़्लो बिन लागू है या नहीं। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें।

**रिटर्न मान:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

निर्दिष्ट करता है कि ओवरफ़्लो बिन लागू है या नहीं। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

निर्दिष्ट करता है स्वचालित ओवरफ़्लो बिन मान। यदि false हो तो OverflowBin प्रॉपर्टी का उपयोग करें।

**रिटर्न मान:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

निर्दिष्ट करता है स्वचालित ओवरफ़्लो बिन मान। यदि false हो तो OverflowBin प्रॉपर्टी का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

निर्दिष्ट करता है ओवरफ़्लो बिन का कस्टम मान। जब IsAutomaticOverflowBin प्रॉपर्टी false पर सेट हो और IsOverflowBin प्रॉपर्टी true हो तब लागू होता है।

**रिटर्न मान:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

निर्दिष्ट करता है ओवरफ़्लो बिन का कस्टम मान। जब IsAutomaticOverflowBin प्रॉपर्टी false पर सेट हो और IsOverflowBin प्रॉपर्टी true हो तब लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

निर्दिष्ट करता है कि अंडरफ़्लो बिन लागू है या नहीं। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें।

**रिटर्न मान:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

निर्दिष्ट करता है कि अंडरफ़्लो बिन लागू है या नहीं। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

निर्दिष्ट करता है स्वचालित अंडरफ़्लो बिन मान। यदि false हो तो UnderflowBin प्रॉपर्टी का उपयोग करें।

**रिटर्न मान:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

निर्दिष्ट करता है स्वचालित अंडरफ़्लो बिन मान। यदि false हो तो UnderflowBin प्रॉपर्टी का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

निर्दिष्ट करता है अंडरफ़्लो बिन का कस्टम मान। जब IsAutomaticUnderflowBin प्रॉपर्टी false पर सेट हो और IsUnderflowBin प्रॉपर्टी true हो तब लागू होता है।

**रिटर्न मान:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

निर्दिष्ट करता है अंडरफ़्लो बिन का कस्टम मान। जब IsAutomaticUnderflowBin प्रॉपर्टी false पर सेट हो और IsUnderflowBin प्रॉपर्टी true हो तब लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |