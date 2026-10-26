---
title: Axis
second_title: Aspose.Slides for Android के लिये Java API रेफ़रेंस
description: चार्ट की अक्ष को दर्शाने वाले ऑब्जेक्ट को संलग्न करता है।
type: docs
url: /hi/com.aspose.slides/axis/
---
**Inheritance:**  
विरासत: java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
सभी लागू इंटरफ़ेस:  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Encapsulates the object that represents a chart's axis.  
एक चार्ट की अक्ष को दर्शाने वाले ऑब्जेक्ट को संलग्न करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | दर्शाता है कि मान अक्ष श्रेणी अक्ष को श्रेणियों के बीच पार करता है या नहीं। |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | दर्शाता है कि मान अक्ष श्रेणी अक्ष को श्रेणियों के बीच पार करता है या नहीं। |
| [getCategoryAxisType()](#getCategoryAxisType--) | श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | IAxis.CategoryAxisType गुण को ऐसा मान सेट करता है जो अक्ष डेटा के आधार पर स्वतः निर्धारित किया जाता है। |
| [getCrossAt()](#getCrossAt--) | अक्ष पर वह बिंदु दर्शाता है जहाँ लंबवत अक्ष इसके साथ क्रॉस करता है। |
| [setCrossAt(float value)](#setCrossAt-float-) | अक्ष पर वह बिंदु दर्शाता है जहाँ लंबवत अक्ष इसके साथ क्रॉस करता है। |
| [getDisplayUnit()](#getDisplayUnit--) | मान अक्ष के लिए डिस्प्ले यूनिट्स का स्केलिंग मान निर्दिष्ट करता है। |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | मान अक्ष के लिए डिस्प्ले यूनिट्स का स्केलिंग मान निर्दिष्ट करता है। |
| [getActualMaxValue()](#getActualMaxValue--) | अक्ष पर वास्तविक अधिकतम मान निर्दिष्ट करता है। |
| [getActualMinValue()](#getActualMinValue--) | अक्ष पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। |
| [getActualMajorUnit()](#getActualMajorUnit--) | अक्ष की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। |
| [getActualMinorUnit()](#getActualMinorUnit--) | अक्ष की वास्तविक गौण इकाई निर्दिष्ट करता है। |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | अक्ष की वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | अक्ष की वास्तविक गौण इकाई स्केल निर्दिष्ट करता है। |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | क्या अधिकतम मान स्वतः असाइन किया गया है, यह दर्शाता है। |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | क्या अधिकतम मान स्वतः असाइन किया गया है, यह दर्शाता है। |
| [getMaxValue()](#getMaxValue--) | मान अक्ष पर अधिकतम मान दर्शाता है। |
| [setMaxValue(double value)](#setMaxValue-double-) | मान अक्ष पर अधिकतम मान दर्शाता है। |
| [getMinorUnit()](#getMinorUnit--) | तारीख या मान अक्ष के लिए गौण इकाइयों को दर्शाता है। |
| [setMinorUnit(double value)](#setMinorUnit-double-) | तारीख या मान अक्ष के लिए गौण इकाइयों को दर्शाता है। |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | क्या अक्ष की गौण इकाई स्वतः असाइन की गई है, यह दर्शाता है। |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | क्या अक्ष की गौण इकाई स्वतः असाइन की गई है, यह दर्शाता है। |
| [getMajorUnit()](#getMajorUnit--) | तारीख या मान अक्ष के लिए प्रमुख इकाइयों को दर्शाता है। |
| [setMajorUnit(double value)](#setMajorUnit-double-) | तारीख या मान अक्ष के लिए प्रमुख इकाइयों को दर्शाता है। |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | क्या अक्ष की प्रमुख इकाई स्वतः असाइन की गई है, यह दर्शाता है। |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | क्या अक्ष की प्रमुख इकाई स्वतः असाइन की गई है, यह दर्शाता है। |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | क्या न्यूनतम मान स्वतः असाइन किया गया है, यह दर्शाता है। |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | क्या न्यूनतम मान स्वतः असाइन किया गया है, यह दर्शाता है। |
| [getMinValue()](#getMinValue--) | मान अक्ष पर न्यूनतम मान दर्शाता है। |
| [setMinValue(double value)](#setMinValue-double-) | मान अक्ष पर न्यूनतम मान दर्शाता है। |
| [isLogarithmic()](#isLogarithmic--) | दर्शाता है कि मान अक्ष का स्केल प्रकार लघुगणकीय है या नहीं। |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | दर्शाता है कि मान अक्ष का स्केल प्रकार लघुगणकीय है या नहीं। |
| [getLogBase()](#getLogBase--) | लघुगणकीय आधार दर्शाता है। |
| [setLogBase(double value)](#setLogBase-double-) | लघुगणकीय आधार दर्शाता है। |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | क्या MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है, दर्शाता है। |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | क्या MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है, दर्शाता है। |
| [isVisible()](#isVisible--) | क्या अक्ष दिखाई देता है, दर्शाता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | क्या अक्ष दिखाई देता है, दर्शाता है। |
| [getMajorTickMark()](#getMajorTickMark--) | निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क का प्रकार दर्शाता है। |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क का प्रकार दर्शाता है। |
| [getMinorTickMark()](#getMinorTickMark--) | निर्दिष्ट अक्ष के लिए गौण टिक मार्क का प्रकार दर्शाता है। |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | निर्दिष्ट अक्ष के लिए गौण टिक मार्क का प्रकार दर्शाता है। |
| [getTickLabelPosition()](#getTickLabelPosition--) | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। |
| [getMajorUnitScale()](#getMajorUnitScale--) | तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [getMinorUnitScale()](#getMinorUnitScale--) | तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। |
| [getBaseUnitScale()](#getBaseUnitScale--) | तारीख अक्ष पर दर्शाए गए सबसे छोटे समय इकाई को निर्दिष्ट करता है। |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | तारीख अक्ष पर दर्शाए गए सबसे छोटे समय इकाई को निर्दिष्ट करता है। |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | चार्ट अक्ष पर गौण ग्रिडलाइन फ़ॉर्मेट दर्शाता है। |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | चार्ट अक्ष पर प्रमुख ग्रिडलाइन फ़ॉर्मेट दर्शाता है। |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | गौण ग्रिडलाइन को छुपाने के लिए MinorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | मुख्य ग्रिडलाइन को छुपाने के लिए MajorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। |
| [getFormat()](#getFormat--) | अक्ष का फ़ॉर्मेट दर्शाता है। |
| [getTextFormat()](#getTextFormat--) | पाठ का फ़ॉर्मेट दर्शाता है। |
| [getTitle()](#getTitle--) | अक्ष का शीर्षक प्राप्त करता है। |
| [getCrossType()](#getCrossType--) | निर्दिष्ट अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, उस स्थान पर CrossType दर्शाता है। |
| [setCrossType(int value)](#setCrossType-int-) | निर्दिष्ट अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, उस स्थान पर CrossType दर्शाता है। |
| [getPosition()](#getPosition--) | अक्ष की स्थिति दर्शाता है। |
| [setPosition(int value)](#setPosition-int-) | अक्ष की स्थिति दर्शाता है। |
| [hasTitle()](#hasTitle--) | निर्धारित करता है कि क्या अक्ष का शीर्षक दृश्यमान है। |
| [setTitle(boolean value)](#setTitle-boolean-) | निर्धारित करता है कि क्या अक्ष का शीर्षक दृश्यमान है। |
| [getNumberFormat()](#getNumberFormat--) | अक्ष लेबल्स के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | अक्ष लेबल्स के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | क्या फ़ॉर्मेट स्रोत डेटा से जुड़ा है, यह दर्शाता है। |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | क्या फ़ॉर्मेट स्रोत डेटा से जुड़ा है, यह दर्शाता है। |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | टिक लेबल्स का घूर्णन कोण दर्शाता है। |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | टिक लेबल्स का घूर्णन कोण दर्शाता है। |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | खींचे जाने वाले लेबल के बीच कितने टिक लेबल्स को छोड़ना है, यह निर्दिष्ट करता है। |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | खींचे जाने वाले लेबल के बीच कितने टिक लेबल्स को छोड़ना है, यह निर्दिष्ट करता है। |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | अगले टिक मार्क को खींचने से पहले कितने टिक मार्क्स को छोड़ना है, यह निर्दिष्ट करता है। |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | अगले टिक मार्क को खींचने से पहले कितने टिक मार्क्स को छोड़ना है, यह निर्दिष्ट करता है। |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। |
| [getLabelOffset()](#getLabelOffset--) | लेबल्स की अक्ष से दूरी निर्दिष्ट करता है। |
| [setLabelOffset(int value)](#setLabelOffset-int-) | लेबल्स की अक्ष से दूरी निर्दिष्ट करता है। |
| [getAggregationType()](#getAggregationType--) | श्रेणी अक्ष का एग्रेगेशन प्रकार (बिनिंग) दर्शाता है। |
| [setAggregationType(int value)](#setAggregationType-int-) | श्रेणी अक्ष का एग्रेगेशन प्रकार (बिनिंग) दर्शाता है। |
| [getBinWidth()](#getBinWidth--) | जब AggregationType गुण को AxisAggregationType.ByBinWidth पर सेट किया गया हो, तब बिन चौड़ाई निर्दिष्ट करता है। |
| [setBinWidth(double value)](#setBinWidth-double-) | जब AggregationType गुण को AxisAggregationType.ByBinWidth पर सेट किया गया हो, तब बिन चौड़ाई निर्दिष्ट करता है। |
| [getNumberOfBins()](#getNumberOfBins--) | जब AggregationType गुण को AxisAggregationType.ByNumberOfBins पर सेट किया गया हो, तब बिनों की संख्या निर्दिष्ट करता है। |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | जब AggregationType गुण को AxisAggregationType.ByNumberOfBins पर सेट किया गया हो, तब बिनों की संख्या निर्दिष्ट करता है। |
| [isOverflowBin()](#isOverflowBin--) | क्या ओवरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | क्या ओवरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। |
| [getOverflowBin()](#getOverflowBin--) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setOverflowBin(double value)](#setOverflowBin-double-) | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [isUnderflowBin()](#isUnderflowBin--) | क्या अंडरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | क्या अंडरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। |
| [getUnderflowBin()](#getUnderflowBin--) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। |

### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट लौटाता है। केवल पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

दर्शाता है कि मान अक्ष श्रेणी अक्ष को श्रेणियों के बीच पार करता है या नहीं। यह गुण केवल श्रेणी अक्षों पर लागू होता है, और 3-डी चार्ट्स पर लागू नहीं होता। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

दर्शाता है कि मान अक्ष श्रेणी अक्ष को श्रेणियों के बीच पार करता है या नहीं। यह गुण केवल श्रेणी अक्षों पर लागू होता है, और 3-डी चार्ट्स पर लागू नहीं होता। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। पढ़ने/लिखने योग्य [CategoryAxisType](../../com.aspose.slides/categoryaxistype)।

**रिटर्न:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। पढ़ने/लिखने योग्य [CategoryAxisType](../../com.aspose.slides/categoryaxistype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType गुण को ऐसा मान सेट करता है जो अक्ष डेटा के आधार पर स्वतः निर्धारित किया जाता है।

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

अक्ष पर वह बिंदु दर्शाता है जहाँ लंबवत अक्ष इसके साथ क्रॉस करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

अक्ष पर वह बिंदु दर्शाता है जहाँ लंबवत अक्ष इसके साथ क्रॉस करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

मान अक्ष के लिए डिस्प्ले यूनिट्स का स्केलिंग मान निर्दिष्ट करता है। पढ़ने/लिखने योग्य [DisplayUnitType](../../com.aspose.slides/displayunittype)।

**रिटर्न:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

मान अक्ष के लिए डिस्प्ले यूनिट्स का स्केलिंग मान निर्दिष्ट करता है। पढ़ने/लिखने योग्य [DisplayUnitType](../../com.aspose.slides/displayunittype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

अक्ष पर वास्तविक अधिकतम मान निर्दिष्ट करता है। वास्तविक मान पाने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**रिटर्न:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

अक्ष पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। वास्तविक मान पाने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**रिटर्न:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

अक्ष की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान पाने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**रिटर्न:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

अक्ष की वास्तविक गौण इकाई निर्दिष्ट करता है। वास्तविक मान पाने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**रिटर्न:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

अक्ष की वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। वास्तविक मान पाने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**रिटर्न:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

अक्ष की वास्तविक गौण इकाई स्केल निर्दिष्ट करता है। वास्तविक मान पाने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें।

**रिटर्न:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

क्या अधिकतम मान स्वतः असाइन किया गया है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

क्या अधिकतम मान स्वतः असाइन किया गया है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

मान अक्ष पर अधिकतम मान दर्शाता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

मान अक्ष पर अधिकतम मान दर्शाता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

तारीख या मान अक्ष के लिए गौण इकाइयों को दर्शाता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

तारीख या मान अक्ष के लिए गौण इकाइयों को दर्शाता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

क्या अक्ष की गौण इकाई स्वतः असाइन की गई है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

क्या अक्ष की गौण इकाई स्वतः असाइन की गई है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

तारीख या मान अक्ष के लिए प्रमुख इकाइयों को दर्शाता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**  
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

तारीख या मान अक्ष के लिए प्रमुख इकाइयों को दर्शाता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

क्या अक्ष की प्रमुख इकाई स्वतः असाइन की गई है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

क्या अक्ष की प्रमुख इकाई स्वतः असाइन की गई है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

क्या न्यूनतम मान स्वतः असाइन किया गया है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

क्या न्यूनतम मान स्वतः असाइन किया गया है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

मान अक्ष पर न्यूनतम मान दर्शाता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**  
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

मान अक्ष पर न्यूनतम मान दर्शाता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

क्या मान अक्ष का स्केल प्रकार लघुगणकीय है या नहीं, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

क्या मान अक्ष का स्केल प्रकार लघुगणकीय है या नहीं, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

लघुगणकीय आधार दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ने/लिखने योग्य double।

**रिटर्न:**  
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

लघुगणकीय आधार दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

क्या MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

क्या MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

क्या अक्ष दिखाई देता है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

क्या अक्ष दिखाई देता है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क का प्रकार दर्शाता है। पढ़ने/लिखने योग्य [TickMarkType](../../com.aspose.slides/tickmarktype)।

**रिटर्न:**  
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क का प्रकार दर्शाता है। पढ़ने/लिखने योग्य [TickMarkType](../../com.aspose.slides/tickmarktype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

निर्दिष्ट अक्ष के लिए गौण टिक मार्क का प्रकार दर्शाता है। पढ़ने/लिखने योग्य [TickMarkType](../../com.aspose.slides/tickmarktype)।

**रिटर्न:**  
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

निर्दिष्ट अक्ष के लिए गौण टिक मार्क का प्रकार दर्शाता है। पढ़ने/लिखने योग्य [TickMarkType](../../com.aspose.slides/tickmarktype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। पढ़ने/लिखने योग्य [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)।

**रिटर्न:**  
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। पढ़ने/लिखने योग्य [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ने/लिखने योग्य [TimeUnitType](../../com.aspose.slides/timeunittype)।

**रिटर्न:**  
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ने/लिखने योग्य [TimeUnitType](../../com.aspose.slides/timeunittype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ने/लिखने योग्य [TimeUnitType](../../com.aspose.slides/timeunittype)।

**रिटर्न:**  
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

तारीख अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ने/लिखने योग्य [TimeUnitType](../../com.aspose.slides/timeunittype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

तारीख अक्ष पर दर्शाए गए सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ने/लिखने योग्य [TimeUnitType](../../com.aspose.slides/timeunittype)।

**रिटर्न:**  
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

तारीख अक्ष पर दर्शाए गए सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ने/लिखने योग्य [TimeUnitType](../../com.aspose.slides/timeunittype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

गौण ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)।

**रिटर्न:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

प्रमुख ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल पढ़ने योग्य [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)।

**रिटर्न:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

गौण ग्रिडलाइन को छुपाने के लिए MinorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। केवल पढ़ने योग्य बूलियन।

**रिटर्न:**  
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

मुख्य ग्रिडलाइन को छुपाने के लिए MajorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। केवल पढ़ने योग्य बूलियन।

**रिटर्न:**  
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

अक्ष का फ़ॉर्मेट दर्शाता है। केवल पढ़ने योग्य [IAxisFormat](../../com.aspose.slides/iaxisformat)।

**रिटर्न:**  
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

पाठ का फ़ॉर्मेट दर्शाता है। केवल पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat)।

**रिटर्न:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

अक्ष का शीर्षक प्राप्त करता है। केवल पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle)।

**रिटर्न:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

निर्दिष्ट अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, उस स्थान पर CrossType दर्शाता है। पढ़ने/लिखने योग्य [CrossesType](../../com.aspose.slides/crossestype)।

**रिटर्न:**  
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

निर्दिष्ट अक्ष पर जहाँ दूसरा अक्ष क्रॉस करता है, उस स्थान पर CrossType दर्शाता है। पढ़ने/लिखने योग्य [CrossesType](../../com.aspose.slides/crossestype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

अक्ष की स्थिति दर्शाता है। पढ़ने/लिखने योग्य [AxisPositionType](../../com.aspose.slides/axispositiontype)।

**रिटर्न:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

अक्ष की स्थिति दर्शाता है। पढ़ने/लिखने योग्य [AxisPositionType](../../com.aspose.slides/axispositiontype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

निर्धारित करता है कि क्या अक्ष का शीर्षक दृश्यमान है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

निर्धारित करता है कि क्या अक्ष का शीर्षक दृश्यमान है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

अक्ष लेबल्स के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

अक्ष लेबल्स के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

क्या फ़ॉर्मेट स्रोत डेटा से जुड़ा है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

क्या फ़ॉर्मेट स्रोत डेटा से जुड़ा है, यह दर्शाता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

टिक लेबल्स का घूर्णन कोण दर्शाता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

टिक लेबल्स का घूर्णन कोण दर्शाता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

खींचे जाने वाले लेबल के बीच कितने टिक लेबल्स को छोड़ना है, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू होता है। पढ़ने/लिखने योग्य long।

**रिटर्न:**  
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

खींचे जाने वाले लेबल के बीच कितने टिक लेबल्स को छोड़ना है, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू होता है। पढ़ने/लिखने योग्य long।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickLabelSpacing गुण का उपयोग करें। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickLabelSpacing गुण का उपयोग करें। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

अगले टिक मार्क को खींचने से पहले कितने टिक मार्क्स को छोड़ना है, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू होता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**  
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

अगले टिक मार्क को खींचने से पहले कितने टिक मार्क्स को छोड़ना है, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू होता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickMarksSpacing गुण का उपयोग करें। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickMarksSpacing गुण का उपयोग करें। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

लेबल्स की अक्ष से दूरी निर्दिष्ट करता है। श्रेणी या तारीख अक्ष पर लागू होता है। मान 0% से 1000% के बीच होना चाहिए। पढ़ने/लिखने योग्य int।

**रिटर्न:**  
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

लेबल्स की अक्ष से दूरी निर्दिष्ट करता है। श्रेणी या तारीख अक्ष पर लागू होता है। मान 0% से 1000% के बीच होना चाहिए। पढ़ने/लिखने योग्य int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

श्रेणी अक्ष का एग्रेगेशन प्रकार (बिनिंग) दर्शाता है। श्रेणी पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**रिटर्न:**  
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

श्रेणी अक्ष का एग्रेगेशन प्रकार (बिनिंग) दर्शाता है। श्रेणी पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

जब AggregationType गुण को AxisAggregationType.ByBinWidth पर सेट किया गया हो, तब बिन चौड़ाई निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखलाओं के साथ उपयोग किया जाता है।

**रिटर्न:**  
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

जब AggregationType गुण को AxisAggregationType.ByBinWidth पर सेट किया गया हो, तब बिन चौड़ाई निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखलाओं के साथ उपयोग किया जाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

जब AggregationType गुण को AxisAggregationType.ByNumberOfBins पर सेट किया गया हो, तब बिनों की संख्या निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखलाओं के साथ उपयोग किया जाता है।

**रिटर्न:**  
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

जब AggregationType गुण को AxisAggregationType.ByNumberOfBins पर सेट किया गया हो, तब बिनों की संख्या निर्दिष्ट करता है। श्रेणी अक्षों पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखलाओं के साथ उपयोग किया जाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

क्या ओवरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें।

**रिटर्न:**  
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

क्या ओवरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: OverflowBin गुण का उपयोग करें।

**रिटर्न:**  
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: OverflowBin गुण का उपयोग करें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin गुण को false पर सेट किया गया हो और IsOverflowBin गुण true हो, तब लागू होता है।

**रिटर्न:**  
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin गुण को false पर सेट किया गया हो और IsOverflowBin गुण true हो, तब लागू होता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

क्या अंडरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें।

**रिटर्न:**  
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

क्या अंडरफ़्लो बिन लागू है, यह निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: UnderflowBin गुण का उपयोग करें।

**रिटर्न:**  
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: UnderflowBin गुण का उपयोग करें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin गुण को false पर सेट किया गया हो और IsUnderflowBin गुण true हो, तब लागू होता है।

**रिटर्न:**  
double

### setUnderfillBin(double value) {#setUnderfillBin-double-}
```
public final void setUnderflowBin(double value)
```

अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin गुण को false पर सेट किया गया हो और IsUnderflowBin गुण true हो, तब लागू होता है।

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

FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**  
[IPresentation](../../com.aspose.slides/ipresentation)