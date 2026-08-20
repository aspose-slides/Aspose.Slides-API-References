---
title: Axis
second_title: Aspose.Slides for Java API संदर्भ
description: एक चार्ट अक्ष को दर्शाने वाले ऑब्जेक्ट को समाहित करता है।
type: docs
url: /hi/com.aspose.slides/axis/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

एक वस्तु को संक्षिप्त करता है जो चार्ट की धुरी का प्रतिनिधित्व करती है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | दर्शाता है कि मूल्य धुरी श्रेणी धुरी को श्रेणियों के बीच पार करती है या नहीं। |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | दर्शाता है कि मूल्य धुरी श्रेणी धुरी को श्रेणियों के बीच पार करती है या नहीं। |
| [getCategoryAxisType()](#getCategoryAxisType--) | श्रेणी धुरी का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | श्रेणी धुरी का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | धुरी डेटा के आधार पर स्वचालित रूप से निर्धारित मान के साथ IAxis.CategoryAxisType प्रॉपर्टी सेट करता है। |
| [getCrossAt()](#getCrossAt--) | धुरी पर वह बिंदु दर्शाता है जहाँ लंबरूप धुरी उसे काटती है। |
| [setCrossAt(float value)](#setCrossAt-float-) | धुरी पर वह बिंदु दर्शाता है जहाँ लंबरूप धुरी उसे काटती है। |
| [getDisplayUnit()](#getDisplayUnit--) | मूल्य धुरी के लिए प्रदर्शित इकाइयों का स्केलिंग मान निर्दिष्ट करता है। |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | मूल्य धुरी के लिए प्रदर्शित इकाइयों का स्केलिंग मान निर्दिष्ट करता है। |
| [getActualMaxValue()](#getActualMaxValue--) | धुरी पर वास्तविक अधिकतम मान निर्दिष्ट करता है। |
| [getActualMinValue()](#getActualMinValue--) | धुरी पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। |
| [getActualMajorUnit()](#getActualMajorUnit--) | धुरी का वास्तविक प्रमुख इकाई निर्दिष्ट करता है। |
| [getActualMinorUnit()](#getActualMinorUnit--) | धुरी का वास्तविक लघु इकाई निर्दिष्ट करता है। |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | धुरी का वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | धुरी का वास्तविक लघु इकाई स्केल निर्दिष्ट करता है। |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | दर्शाता है कि अधिकतम मान स्वचालित रूप से निर्धारित किया गया है या नहीं। |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | दर्शाता है कि अधिकतम मान स्वचालित रूप से निर्धारित किया गया है या नहीं। |
| [getMaxValue()](#getMaxValue--) | मूल्य धुरी पर अधिकतम मान दर्शाता है। |
| [setMaxValue(double value)](#setMaxValue-double-) | मूल्य धुरी पर अधिकतम मान दर्शाता है। |
| [getMinorUnit()](#getMinorUnit--) | तिथि या मूल्य धुरी के लिए लघु इकाइयाँ दर्शाता है। |
| [setMinorUnit(double value)](#setMinorUnit-double-) | तिथि या मूल्य धुरी के लिए लघु इकाइयाँ दर्शाता है। |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | दर्शाता है कि धुरी की लघु इकाई स्वचालित रूप से निर्धारित की गई है या नहीं। |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | दर्शाता है कि धुरी की लघु इकाई स्वचालित रूप से निर्धारित की गई है या नहीं। |
| [getMajorUnit()](#getMajorUnit--) | तिथि या मूल्य धुरी के लिए प्रमुख इकाइयाँ दर्शाता है। |
| [setMajorUnit(double value)](#setMajorUnit-double-) | तिथि या मूल्य धुरी के लिए प्रमुख इकाइयाँ दर्शाता है। |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | दर्शाता है कि धुरी की प्रमुख इकाई स्वचालित रूप से निर्धारित की गई है या नहीं। |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | दर्शाता है कि धुरी की प्रमुख इकाई स्वचालित रूप से निर्धारित की गई है या नहीं। |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | दर्शाता है कि न्यूनतम मान स्वचालित रूप से निर्धारित किया गया है या नहीं। |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | दर्शाता है कि न्यूनतम मान स्वचालित रूप से निर्धारित किया गया है या नहीं। |
| [getMinValue()](#getMinValue--) | मूल्य धुरी पर न्यूनतम मान दर्शाता है। |
| [setMinValue(double value)](#setMinValue-double-) | मूल्य धुरी पर न्यूनतम मान दर्शाता है। |
| [isLogarithmic()](#isLogarithmic--) | दर्शाता है कि मूल्य धुरी का स्केल प्रकार लघुगणकीय है या नहीं। |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | दर्शाता है कि मूल्य धुरी का स्केल प्रकार लघुगणकीय है या नहीं। |
| [getLogBase()](#getLogBase--) | लघुगणकीय आधार दर्शाता है। |
| [setLogBase(double value)](#setLogBase-double-) | लघुगणकीय आधार दर्शाता है। |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | दर्शाता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | दर्शाता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। |
| [isVisible()](#isVisible--) | दर्शाता है कि धुरी दृश्य है या नहीं। |
| [setVisible(boolean value)](#setVisible-boolean-) | दर्शाता है कि धुरी दृश्य है या नहीं। |
| [getMajorTickMark()](#getMajorTickMark--) | निर्दिष्ट धुरी के प्रमुख टिक मार्क प्रकार को दर्शाता है। |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | निर्दिष्ट धुरी के प्रमुख टिक मार्क प्रकार को दर्शाता है। |
| [getMinorTickMark()](#getMinorTickMark--) | निर्दिष्ट धुरी के लघु टिक मार्क प्रकार को दर्शाता है। |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | निर्दिष्ट धुरी के लघु टिक मार्क प्रकार को दर्शाता है। |
| [getTickLabelPosition()](#getTickLabelPosition--) | निर्दिष्ट धुरी पर टिक-मार्क लेबल की स्थिति दर्शाता है। |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | निर्दिष्ट धुरी पर टिक-मार्क लेबल की स्थिति दर्शाता है। |
| [getMajorUnitScale()](#getMajorUnitScale--) | तिथि धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | तिथि धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [getMinorUnitScale()](#getMinorUnitScale--) | तिथि धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | तिथि धुरी के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [getBaseUnitScale()](#getBaseUnitScale--) | तिथि धुरी पर प्रदर्शित सबसे छोटी समय इकाई निर्दिष्ट करता है। |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | तिथि धुरी पर प्रदर्शित सबसे छोटी समय इकाई निर्दिष्ट करता है। |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | चार्ट धुरी पर लघु ग्रिडलाइन का स्वरूप दर्शाता है। |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | चार्ट धुरी पर प्रमुख ग्रिडलाइन का स्वरूप दर्शाता है। |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | न्यूनतम ग्रिडलाइन को छुपाने के लिए MinorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | प्रमुख ग्रिडलाइन को छुपाने के लिए MajorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। |
| [getFormat()](#getFormat--) | धुरी का स्वरूप दर्शाता है। |
| [getTextFormat()](#getTextFormat--) | पाठ का स्वरूप दर्शाता है। |
| [getTitle()](#getTitle--) | धुरी का शीर्षक प्राप्त करता है। |
| [getCrossType()](#getCrossType--) | निर्दिष्ट धुरी पर वह CrossType दर्शाता है जहाँ दूसरी धुरी उससे मिलती है। |
| [setCrossType(int value)](#setCrossType-int-) | निर्दिष्ट धुरी पर वह CrossType दर्शाता है जहाँ दूसरी धुरी उससे मिलती है। |
| [getPosition()](#getPosition--) | धुरी की स्थिति दर्शाता है। |
| [setPosition(int value)](#setPosition-int-) | धुरी की स्थिति दर्शाता है। |
| [hasTitle()](#hasTitle--) | निर्धारित करता है कि धुरी का शीर्षक दृश्यमान है या नहीं। |
| [setTitle(boolean value)](#setTitle-boolean-) | निर्धारित करता है कि धुरी का शीर्षक दृश्यमान है या नहीं। |
| [getNumberFormat()](#getNumberFormat--) | धुरी लेबल्स के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | धुरी लेबल्स के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | दर्शाता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | दर्शाता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | टिक लेबल्स का घूर्णन कोण दर्शाता है। |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | टिक लेबल्स का घूर्णन कोण दर्शाता है। |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | ड्रॉ किए गए लेबल के बीच छूटे जाने वाले टिक लेबल की संख्या निर्दिष्ट करता है। |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | ड्रॉ किए गए लेबल के बीच छूटे जाने वाले टिक लेबल की संख्या निर्दिष्ट करता है। |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | अगला टिक मार्क ड्रॉ करने से पहले किन टिक मार्कों को छोड़ना है, उन पर संख्या निर्दिष्ट करता है। |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | अगला टिक मार्क ड्रॉ करने से पहले किन टिक मार्कों को छोड़ना है, उन पर संख्या निर्दिष्ट करता है। |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | स्वचालित टिक मार्क स्पेसिंग मान निर्दिष्ट करता है। |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | स्वचालित टिक मार्क स्पेसिंग मान निर्दिष्ट करता है। |
| [getLabelOffset()](#getLabelOffset--) | लेबल्स की धुरी से दूरी निर्दिष्ट करता है। |
| [setLabelOffset(int value)](#setLabelOffset-int-) | लेबल्स की धुरी से दूरी निर्दिष्ट करता है। |
| [getAggregationType()](#getAggregationType--) | श्रेणी धुरी (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। |
| [setAggregationType(int value)](#setAggregationType-int-) | श्रेणी धुरी (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। |
| [getBinWidth()](#getBinWidth--) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट हो, तब बिन की चौड़ाई निर्दिष्ट करता है। |
| [setBinWidth(double value)](#setBinWidth-double-) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट हो, तब बिन की चौड़ाई निर्दिष्ट करता है। |
| [getNumberOfBins()](#getNumberOfBins--) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तब बिनों की संख्या निर्दिष्ट करता है। |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तब बिनों की संख्या निर्दिष्ट करता है। |
| [isOverflowBin()](#isOverflowBin--) | दर्शाता है कि ओवरफ़्लो बिन लागू किया गया है या नहीं। |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | दर्शाता है कि ओवरफ़्लो बिन लागू किया गया है या नहीं। |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। |
| [getOverflowBin()](#getOverflowBin--) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setOverflowBin(double value)](#setOverflowBin-double-) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [isUnderflowBin()](#isUnderflowBin--) | दर्शाता है कि अंडरफ़्लो बिन लागू किया गया है या नहीं। |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | दर्शाता है कि अंडरफ़्लो बिन लागू किया गया है या नहीं। |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। |
| [getUnderflowBin()](#getUnderflowBin--) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) | FillFormat का पेरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पेरेंट प्रस्तुति लौटाता है। |

### getChart() {#getChart--}
```
public final IChart getChart()
```

पेरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart).

**वापसी:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

निर्देशित करता है कि मूल्य धुरी श्रेणी धृति को श्रेणियों के बीच पार करती है या नहीं। यह प्रॉपर्टी केवल श्रेणी धृतियों पर लागू होती है, तथा 3-D चार्ट पर लागू नहीं होती। पढ़ें/लिखें बूलियन।

**वापसी:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

निर्देशित करता है कि मूल्य धुरी श्रेणी धृति को श्रेणियों के बीच पार करती है या नहीं। यह प्रॉपर्टी केवल श्रेणी धृतियों पर लागू होती है, तथा 3-D चार्ट पर लागू नहीं होती। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

श्रेणी धृति का प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [CategoryAxisType](../../com.aspose.slides/categoryaxistype)।

**वापसी:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

श्रेणी धृति का प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [CategoryAxisType](../../com.aspose.slides/categoryaxistype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType प्रॉपर्टी को ऐसे मान से सेट करता है जो धुरी डेटा के आधार पर स्वचालित रूप से निर्धारित होता है।

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

धुरी पर वह बिंदु दर्शाता है जहाँ लंबरूप धुरी उसे काटती है। पढ़ें/लिखें float।

**वापसी:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

धुरी पर वह बिंदु दर्शाता है जहाँ लंबरूप धुरी उसे काटती है। पढ़ें/लिखें float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

मूल्य धुरी के लिए प्रदर्शित इकाइयों का स्केलिंग मान निर्दिष्ट करता है। पढ़ें/लिखें [DisplayUnitType](../../com.aspose.slides/displayunittype)।

**वापसी:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

मूल्य धुरी के लिए प्रदर्शित इकाइयों का स्केलिंग मान निर्दिष्ट करता है। पढ़ें/लिखें [DisplayUnitType](../../com.aspose.slides/displayunittype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

धुरी पर वास्तविक अधिकतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को बुलाएँ।

**वापसी:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

धुरी पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को बुलाएँ।

**वापसी:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

धुरी का वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को बुलाएँ।

**वापसी:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

धुरी का वास्तविक लघु इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को बुलाएँ।

**वापसी:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

धुरी का वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को बुलाएँ।

**वापसी:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

धुरी का वास्तविक लघु इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को बुलाएँ।

**वापसी:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

दर्शाता है कि अधिकतम मान स्वचालित रूप से निर्धारित किया गया है या नहीं। पढ़ें/लिखें बूलियन।

**वापसी:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

दर्शाता है कि अधिकतम मान स्वचालित रूप से निर्धारित किया गया है या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

मूल्य धुरी पर अधिकतम मान दर्शाता है। पढ़ें/लिखें डबल।

**वापसी:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

मूल्य धुरी पर अधिकतम मान दर्शाता है। पढ़ें/लिखें डबल।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

तिथि या मूल्य धुरी के लिए लघु इकाइयाँ दर्शाता है। पढ़ें/लिखें डबल।

**वापसी:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

तिथि या मूल्य धुरी के लिए लघु इकाइयाँ दर्शाता है। पढ़ें/लिखें डबल।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Indicates whether the minor unit of the axis is automatically assigned. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Indicates whether the minor unit of the axis is automatically assigned. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Represents the major units for the date or value axis. पढ़ें/लिखें double.

**रिटर्न:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Represents the major units for the date or value axis. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Indicates whether the major unit of the axis is automatically assigned. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Indicates whether the major unit of the axis is automatically assigned. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Indicates whether the min value is automatically assigned. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Indicates whether the min value is automatically assigned. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Represents the minimum value on the value axis. पढ़ें/लिखें double.

**रिटर्न:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Represents the minimum value on the value axis. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Represents if the value axis scale type is logarithmic or not. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Represents if the value axis scale type is logarithmic or not. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Represents the logarithmic base. Default value is 10. पढ़ें/लिखें double.

**रिटर्न:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Represents the logarithmic base. Default value is 10. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Represents if MS PowerPoint plots data points from last to first. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Represents if MS PowerPoint plots data points from last to first. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Represents if the axis is visible. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Represents if the axis is visible. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Represents the type of major tick mark for the specified axis. पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**रिटर्न:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Represents the type of major tick mark for the specified axis. पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Represents the type of minor tick mark for the specified axis. पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**रिटर्न:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Represents the type of minor tick mark for the specified axis. पढ़ें/लिखें [TickMarkType](../../com.aspose.slides/tickmarktype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Represents the position of tick-mark labels on the specified axis. पढ़ें/लिखें [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**रिटर्न:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Represents the position of tick-mark labels on the specified axis. पढ़ें/लिखें [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Represents the major unit scale for the date axis. पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**रिटर्न:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Represents the major unit scale for the date axis. पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Represents the major unit scale for the date axis. पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**रिटर्न:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Represents the major unit scale for the date axis. पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Specifies the smallest time unit that is represented on the date axis. पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**रिटर्न:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Specifies the smallest time unit that is represented on the date axis. पढ़ें/लिखें [TimeUnitType](../../com.aspose.slides/timeunittype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Represents minor gridlines format on a chart axis. केवल- पढ़ें [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**रिटर्न:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Represents major gridlines format on a chart axis. केवल- पढ़ें [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**रिटर्न:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. केवल- पढ़ें boolean.

**रिटर्न:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. केवल- पढ़ें boolean.

**रिटर्न:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Represents format of axis. केवल- पढ़ें [IAxisFormat](../../com.aspose.slides/iaxisformat).

**रिटर्न:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Represents format of text. केवल- पढ़ें [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**रिटर्न:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Gets the axis' title. केवल- पढ़ें [IChartTitle](../../com.aspose.slides/icharttitle).

**रिटर्न:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Represents the CrossType on the specified axis where the other axis crosses. पढ़ें/लिखें [CrossesType](../../com.aspose.slides/crossestype).

**रिटर्न:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Represents the CrossType on the specified axis where the other axis crosses. पढ़ें/लिखें [CrossesType](../../com.aspose.slides/crossestype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Represents position of axis. पढ़ें/लिखें [AxisPositionType](../../com.aspose.slides/axispositiontype).

**रिटर्न:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Represents position of axis. पढ़ें/लिखें [AxisPositionType](../../com.aspose.slides/axispositiontype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Determines whether a axis has a visible title. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Determines whether a axis has a visible title. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Represents the format string for the Axis Labels. पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Represents the format string for the Axis Labels. पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Indicates whether the format is linked source data. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Indicates whether the format is linked source data. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Represents the rotation angle of tick labels. पढ़ें/लिखें float.

**रिटर्न:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Represents the rotation angle of tick labels. पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. पढ़ें/लिखें long.

**रिटर्न:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. पढ़ें/लिखें long.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. पढ़ें/लिखें int.

**रिटर्न:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. पढ़ें/लिखें int.

**रिटर्न:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

श्रेणी अक्ष (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। श्रेणी पर लागू होता है। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है।

**रिटर्न:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

श्रेणी अक्ष (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। श्रेणी पर लागू होता है। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByBinWidth पर सेट किया गया हो तो बिन चौड़ाई निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है।

**रिटर्न:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByBinWidth पर सेट किया गया हो तो बिन चौड़ाई निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByNumberOfBins पर सेट किया गया हो तो बिनों की संख्या निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है।

**रिटर्न:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByNumberOfBins पर सेट किया गया हो तो बिनों की संख्या निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

यदि ओवरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें।

**रिटर्न:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

यदि ओवरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: OverflowBin प्रॉपर्टी का उपयोग करें।

**रिटर्न:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: OverflowBin प्रॉपर्टी का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin प्रॉपर्टी false पर सेट की गई हो और IsOverflowBin प्रॉपर्टी true हो तो लागू होता है।

**रिटर्न:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin प्रॉपर्टी false पर सेट की गई हो और IsOverflowBin प्रॉपर्टी true हो तो लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

यदि अंडरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें।

**रिटर्न:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

यदि अंडरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: UnderflowBin प्रॉपर्टी का उपयोग करें।

**रिटर्न:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: UnderflowBin प्रॉपर्टी का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin प्रॉपर्टी false पर सेट की गई हो और IsUnderflowBin प्रॉपर्टी true हो तो लागू होता है।

**रिटर्न:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin प्रॉपर्टी false पर सेट की गई हो और IsUnderflowBin प्रॉपर्टी true हो तो लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat की पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)